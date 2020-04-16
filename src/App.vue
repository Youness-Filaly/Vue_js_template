<template>
  <div id="app">
    <!-- header-start -->
    <Header></Header>

    <!-- header-end -->


    <!-- slider_area_start -->
    <Slider></Slider>
    <!-- slider_area_end -->

     <!-- About us-start -->
    <Aboutus></Aboutus>

    <!-- About us-end -->
    <!-- How Work-start -->
    <HowWork></HowWork>

    <!-- How Work-end -->
    <!-- pricing_area start -->
      <Pricing ></Pricing>
    <!-- pricing_are end -->
    <!-- footer start -->
      <Footer></Footer>
    <!--/ footer end  -->
    
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Slider from './components/Slider.vue'
import Pricing from './components/Pricing.vue'
import Footer from './components/Footer.vue'
import Aboutus from './components/Aboutus.vue'
import HowWork from './components/HowWork.vue';
//import {BootstrapVue, IconPlugin} from 'bootstrap-vue'

export default {
  name: "App",
  components:{
    Header,
    Slider,
    Aboutus,
    HowWork,
    Pricing,
    Footer
  }
};
</script>

<style></style>
