<template>
  
  <signup-form />
  
</template>

<script>
import SignupForm from './components/SignupForm.vue';

export default {
  name: 'App',
  components: {
    SignupForm
  }
}

</script>

<style>
#app {
  font-family: Avenir, Arial, Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: #2c3e50;
  margin-top: 60px;
}
body {
  margin: 0;
  background: #eee;
}
</style>
