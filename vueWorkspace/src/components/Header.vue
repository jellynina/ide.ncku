<template>
  <div class="g-header-outline">
      <div class="g-header-position">
        <div class="g-header">
            <div class="head-col head-col-logo">
              <h1 class="h1"><a href="/bin/home.php"><img alt="成功大學工業設計系" class="g-logo-img" src="/ezfiles/417/1417/img/3131/logo.png"/></a></h1>
            </div>
            <div class="head-col head-col-nav">
              <ul class="head-nav-list">
                <li><a href="/bin/home.php ">首頁</a></li>
                <li><a href="/files/11-1417-83-preview.php?Lang=zh-tw">最新消息</a></li>
                <li><a href="/files/90-1417-1.php?Lang=zh-tw">系上成員</a></li>
                <li><a href="/files/90-1417-4.php?Lang=zh-tw">系上課程</a></li>
                <li><a href="/files/90-1417-5.php?Lang=zh-tw">學生實習工廠</a></li>
                <li><a href="http://www.ide.ncku.edu.tw/sposad/" target="_blank">招生資訊</a></li>
                <li><a href="http://www.ide.ncku.edu.tw/sposad/" target="_blank">表單下載</a></li>
                <li><a href="http://www.ide.ncku.edu.tw/sposad/" target="_blank">其他連結</a></li>
              </ul>
            </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
}
</script>

<style lang="scss">



$g-max-width: 1200px;
$g-side-padding: 15px;
$g-head-index: 300;
@mixin reset{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  list-style: none;
}


.g-header-outline{
  width: 100%;
  position: relative;
  padding: 24px 0;
  height: 132px;
}

.g-header-position{
  width: 100%;
  display: block;
  position: fixed;
  top: 0;;
  left: 0;
  padding: 12px 0;
  z-index: $g-head-index;
  background-color: #FFF;
}
.g-header{
  width: 100%;
  max-width: $g-max-width;
  padding: 0px 6px;
  position: relative;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  background-color: #FFF;

  .h1{
    font-size: 18px;
  }
}

.g-logo-img{
  width: 200px;
  height: 83px;
  display: block;
}

.head-col-logo{
  flex-grow: 1;
}
.head-col-nav{
  flex-grow: 2;
}

.head-nav-list{
  @include reset();
  display: flex;
  justify-content: flex-end;
  li{
    padding: 0 6px;
  }
}

</style>
