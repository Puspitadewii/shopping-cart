<template>
  <div id="app">
    <Header />
    <div>
      <ProducList />
    </div>
  </div>
</template>

<script>
import Header from './components/Header';
import ProducList from './components/ProductList';


export default {
  name: 'App',
  components: {
    Header,
    ProducList,
    
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
}
</style>
