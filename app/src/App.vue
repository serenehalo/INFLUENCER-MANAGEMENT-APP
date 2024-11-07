<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </nav>
  <router-view/>
  </div>
</template>

<script>

//import HomePage from './components/Home.vue';
//import AboutPage from './components/About.vue';


export default {
  name: 'App',
  components: {
    
    //HomePage,
    //AboutPage
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
