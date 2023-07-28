<script setup>
  import AboutView from "./views/AboutView.vue"
  import HomeView from "./views/HomeView.vue"
</script>
<template>
  <header>HEADER</header>
  <aside>
    <nav class="menu">
    <router-link to="/" class="home" >Home</router-link>
    <br>
     <router-link to="about" class="about">Sobre</router-link>     


    </nav>
  </aside>
  <main>
  <router-view/>
  </main>
  <footer>FOOTER</footer>
</template>

<style scoped>
.menu{
  display: flex;
  flex-direction: column;
  gap: 1rem;}
.home{
background-color: cadetblue;
display: flex


}
.about{
background-color: cadetblue;  
}
</style>
