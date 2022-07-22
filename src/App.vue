<template>
  <NavBar></NavBar>
  <Content></Content>
  <FooterView></FooterView>
</template>

<script>
import NavBar from './components/navigation/NavbarView.vue'
import Content from './components/content/ContentView.vue';
import FooterView from './components/footer/FooterView.vue';

export default {
  components:{
    NavBar,
    Content,
    FooterView,

  }
}
</script>

<style>
body{
  font-family: sans-serif;
  padding: 0;
  margin: 0;
}
#app{
  display: flex;
  height: 100vh;
  flex-direction: column;
}
</style>
