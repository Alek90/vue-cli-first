<template>
  <div id="app">
    <Title/>
    <Hero/>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Title from './components/Title.vue'
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld
    Title,
    Hero
  }
}
</script>

<style>
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

</style>
