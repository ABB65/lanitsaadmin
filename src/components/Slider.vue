<template>
  <div>
    <Dropdown class="sliderall"></Dropdown>
    <SlideSet></SlideSet>
   </div>
</template>

<script>
  import Dropdown from './GlobalComponent/Dropdown'
  import SlideSet from './SlideComponents/SlideSet'
  export default {
    name: 'Slider',
    components: {
      Dropdown,
      SlideSet,
    },
    data() {
      return {
        msg: 'Lanista Gladio Blog Slide'
      }
    }
  }
</script>
<style lang="less" scoped>
  @nbfcolor: #303030;
  @bgcolor: #ffffff;
  @incolor: #B5B5B5;
  @redcolor: #e33;
  @pagebgcolor: #E5E5E5;
  @btntextcolor: #eee;
  @headingfont: 'Kanit', sans-serif;
  @contentfont: 'Exo', sans-serif;

  .sliderall {
   
    text-align: center;
    margin: 2rem
  }
</style>
