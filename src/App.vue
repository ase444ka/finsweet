<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <button>Kuku ase444ka</button>
    <br>
    <svg>
      <use href="@/assets/sprites.svg#twitter"></use>
    </svg>
    <br>
    <svg>
      <use href="@/assets/sprites.svg#instagram"></use>
    </svg>
    <br>
    <svg>
      <use href="@/assets/sprites.svg#linkedin"></use>
    </svg>
    <br>
    <svg>
      <use href="@/assets/sprites.svg#facebook"></use>
    </svg>
  </header>

  <RouterView />
</template>

<style scoped lang="scss">


</style>
