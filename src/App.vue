<template>
<LearningVue msg="Welcome to Your Vue.js App" title="Learning Vue here" />
<LocalWeather />
</template>

<script>
import LearningVue from './components/LearningVue.vue'
import LocalWeather from './components/LocalWeather'

export default {
  name: 'App',
  components: {
    LearningVue,
    LocalWeather
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
