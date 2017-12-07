<template>
<div>
  <div class="course-head parentOf-absolute">
    <div class="head-containt">
      <h1 class="h1 text-center">課程規劃</h1>
      <div class="head-nav-list">
        <a href="#coursePlan" class="btn-action scroll"><span class="btn-action-txt">規劃<br>重點 </span></a>
      <a href="#underGraduated" class="btn-action scroll"><span class="btn-action-txt">大學部<br>課程</span></a>
      <a href="#graduated" class="btn-action scroll"><span class="btn-action-txt">碩博班<br>課程</span> </a>
      <a href="#special" class="btn-action scroll"><span class="btn-action-txt">碩專班<br>課程</span> </a>
      </div>
    </div>
    <img class="absolute-base-img" src="http://bgc004.web.ncku.edu.tw/ezfiles/417/1417/img/3139/01.jpg" alt="國立成功大學系上課程">
  </div>
  <img src="http://bgc004.web.ncku.edu.tw/ezfiles/417/1417/img/3139/02.jpg" alt="Norway" width="100%" height="auto">
  <img src="http://bgc004.web.ncku.edu.tw/ezfiles/417/1417/img/3139/03.jpg" alt="Norway" width="100%" height="auto">
  <div class="big-button-group" style="background:#f9ede9">
    <a href="http://www.ide.ncku.edu.tw/root/files/2012/11/1/4629">大學部相關修業辦法</a>
    <a href="http://www.ide.ncku.edu.tw/root/files/2010/10/29/221">工設系通識教育目標與規定</a>
  </div>
  <img src="http://bgc004.web.ncku.edu.tw/ezfiles/417/1417/img/3139/04.jpg" alt="Norway" width="100%" height="auto">
  <img src="http://bgc004.web.ncku.edu.tw/ezfiles/417/1417/img/3139/05--.jpg" alt="Norway" width="100%" height="auto">
  <div class="big-button-group" style="background:#f9ede9">
    <a href="http://www.ide.ncku.edu.tw/root/files/2010/10/18/86">工設所碩士課程相關修業辦法</a>
    <a href="http://www.ide.ncku.edu.tw/root/files/2012/11/1/4628">工設所博士課程相關修業辦法</a>
  </div>
  <img src="http://bgc004.web.ncku.edu.tw/ezfiles/417/1417/img/3139/06--.jpg" alt="Norway" width="100%" height="auto">
  <div class="big-button-group" style="background:#f9e8dc">
    <a href="http://www.ide.ncku.edu.tw/root/files/2010/10/18/96">工設所碩專課程相關修業辦法</a>
  </div>
</div>

</template>
<script>
export default {

}
</script>
<style lang="scss">
.text-center{
  text-align: center;
}
.parentOf-absolute{
  display: block;
  width: 100%;
  position: relative;
}
.absolute-base-img{
  display: block;
  position: absolute;
  width: 100%;
  height: auto;
  top: 0;
  left: 0;
}

///
.course-head{
  width: 100%;
  position: relative;
  .absolute-base-img{
    position: relative;
  }
  .head-containt{
    display: block;
    z-index: 10;
    color: #FFFFFF;
    position: absolute;
    width: 100%;
    left: 0;
    top: 50%;
    transform: translateY(-80%);
  }
  .absolute-base-img{
    z-index: 1;
  }


  //// text style
  .h1{
    font-size: 44px;
    text-shadow: 0 2px 1px rgba(#000, .2);
  }
}

.head-nav-list{
  display: flex;
  justify-content: center;
  .btn-action{
    width: 120px;
    height: 120px;
    border: 1px #FFFFFF solid;
    background-color: rgba(#000, .2);
    border-radius: 50%;
    flex-flow: 1;
    margin-right: 24px;
    display: block;
    position: relative;
    transition: ease-in .3s;
  }
  .btn-action-txt{
    position: absolute;
    width: 100%;
    left: 0;
    top: 50%;
    transform: translateY(-50%);
    color: #FFFFFF;
    text-align: center;
    font-size: 16px;
    font-weight: lighter;
    letter-spacing: 5px;
  }

  .btn-action:hover{
    background-color: rgba(#000, .4);
  }
}


</style>
