<script setup>
import { RouterLink, RouterView } from 'vue-router'
import SideBar from '@/views/Home/components/SideBar.vue'
import PostNews from '@/views/Home/components/PostNews.vue';
import Menu from '@/views/Home/components/Menu.vue';
</script>

<template>
  <SideBar />
  <PostNews />
  <Menu />
</template>

<style scoped>

</style>
