<template>
  <div id="app">
    <Header />
    <Categories />
  </div>
</template>

<script>
  import Header from './components/Header.vue';
  import Categories from './components/Categories.vue'
  
  export default {
    name: 'App',
    components: {
      Header,
      Categories
    }
  }
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,300;0,500;0,700;0,900;1,400&display=swap');

#app{
  font-family: 'Roboto';
}
</style>
