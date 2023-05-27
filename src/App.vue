<template>
  <head>
    <meta name="viewport" content="width-device-width, initial-scale=1.0">
    <link href="../dist/output.css" rel="stylesheet">
  </head>
  <div>
    <LoginScreen></LoginScreen>
  </div>
</template>

<script>
import LoginScreen from './components/LoginScreen.vue';

export default {
  name: 'App',
  components: {
    LoginScreen
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
