<template>
  <div class="container">
    <div class="row">
      <Header/>
      <Article/>
      <Aside/>
    </div>
    <Footer/>
  </div>
<!-- 576px	Small  ≥576px	Medium ≥768px	Large ≥992px	超大  ≥1200px	XX-大≥1400px -->
</template>
<script lang="ts" setup>
import Header from './components/Header.vue'
import Article from './components/Article.vue'
import Aside from './components/Aside.vue'
import Footer from './components/Footer.vue'
</script>
<style>
</style>
