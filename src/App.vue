<template>
  <div id="app">
    <CountryList/>
  </div>
</template>

<script>
import CountryList from './components/CountryList.vue'

export default {
  name: 'App',
  components: {
    CountryList
  }
}
</script>

<style>
body{
    background-color: #f9f4ef;
    font-family: 'Poppins', sans-serif;
    
}
</style>
