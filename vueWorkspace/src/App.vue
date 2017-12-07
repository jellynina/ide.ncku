<template>
  <div id="app">
    <!-- ePage outliner opening -->
    <div class="outer-outer">
      <div class="outer layout_type">
        <div class="container">
          <div class="container-inner"> <!---->

            <TheHeader/>
            <div class="fake-content">
              <p>here are the content zpne</p>
              <coursePage/>
            </div>

          </div><!-- ePage outliner closing -->
        </div>
      </div>
    </div><!---->



  </div>
</template>

<script>
import TheHeader from './components/Header.vue'
import ideMap from './components/Map.vue'
import coursePage from './components/CoursePage.vue'
export default {
  components:{
    TheHeader,
    ideMap,
    coursePage

  }
}
</script>

<style lang="scss">
/*
  for devlop
*/

img{
  background-color: rgba( #61BEE1, .3);
  border: 1px dashed rgba( #2FA3E1, .5);
  box-sizing: border-box;

  &:before {
    text-align: center;
    color: #BD2F49;
    font-weight: 700;
  }
}


.fake-content{
  padding: 12px 0;
}


</style>
