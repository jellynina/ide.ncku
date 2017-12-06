<template>
  <div>
    <div class="traffic-info">
      <div class="map">
        <iframe frameborder="0" height="430" width="450" scrolling="no" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3672.69371670344!2d120.21509358707382!3d22.998287680103953!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x346e76f2a4f5d735%3A0xef8c477b3bf63a73!2z5ZyL56uL5oiQ5Yqf5aSn5a245bel5qWt6Kit6KiI5a2457O7!5e0!3m2!1szh-TW!2stw!4v1509900947501"></iframe>
      </div>
      <img src="http://bgc004.web.ncku.edu.tw/ezfiles/417/1417/img/3139/img-trafficinfoBG-new-09.jpg" alt="國立成功大學工業設計系-交通資訊" class="traffic-image">
    </div>
  </div>
</template>
<script>
export default {

}
</script>

<style lang="scss">

.traffic-info{
  position: relative;
  display: block;
  width: 100%;

  .traffic-image{
    position: absolute;
    width: 100%;
    max-width: 1170px;
    height: auto;
    top: 0;
    left: 0;
  }

  .map{
    position: relative;
    z-index: 10;
    width: 430px;
    padding: 45px 25px;
  }
}

.traffic-image{
  display: block;
  width: 100%;
}
</style>
