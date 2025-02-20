<script setup>
import MyCover from '@/components/MyCover.vue'
import MyHeader from '@/components/MyHeader.vue'
import {RouterLink, RouterView} from 'vue-router';
import HelloWorld from './components/HelloWorld.vue';
</script>

<template>
  <MyHeader />
  <main>
    <MyCover />
  </main>

  <RouterView />
</template>

<style scoped lang="scss">


</style>
