<template>
  <div class="wrapper">
    <Header></Header>
    <Main></Main>
    <Footer></Footer>
  </div>
</template>

<script>
import Footer from './components/Footer.vue';
import Header from './components/Header.vue';
import Main from './components/Main.vue';

export default {
    components: { Header, Main, Footer }
}
</script> 

<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: arial;
}

a {
    text-decoration: none;
}
ul {
    list-style: none;
}

.container {
    width: 1140px;
    margin: 0 auto;
}
</style>
