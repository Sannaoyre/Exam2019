<template>
  <div id="app">

      <Header></Header>
      <About></About>
      <br><br><br><br>
      <Icons></Icons>
      <Progress></Progress>

  </div>
</template>

<script>
import Header from './components/Header.vue';
import About from './components/About.vue';
import Icons from './components/Icons.vue';
import Progress from './components/Progress.vue';




export default {
  name: 'App',
  components: {
    Header,
    About,
    Icons,
    Progress
   }
}


</script>



<style lang="scss">
@import '@/styles/main.scss';

body{
  background-color: $primary-black;
}
</style>
