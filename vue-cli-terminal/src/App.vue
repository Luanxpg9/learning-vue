<template>
  <div id='app'>
    <buttonVue></buttonVue>
  </div>
</template>


<script>
  import buttonVue from './buttonVue';
  export default {
    name: 'App',
    components: {
      buttonVue
    },
  }
</script>

<style>
#app {
  color: #2c3e50;
  margin-top: 60px;
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}
</style>
