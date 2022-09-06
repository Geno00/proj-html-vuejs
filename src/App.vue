<template>
  <div id="app">
   <MyHeader/>
   <MyMain/>
   <MyFooter/>
  </div>
</template>

<script>
import MyHeader from '@/components/MyHeader.vue';
import MyMain from '@/components/MyMain.vue';
import MyFooter from '@/components/MyFooter.vue';
import "./assets/style/general.scss";


export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFooter
  }
}
</script>

<style lang="scss">
  
</style>
