<template>
  <div id="app">
    <Header/>
    <QuestionBox/>
  </div>
</template>

<script>
import Header from './components/Header'
import QuestionBox from './components/QuestionBox.vue'


export default {
  name: 'app',
  components: {
    Header,
    QuestionBox
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
