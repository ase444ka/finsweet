<script setup>
import {RouterLink, RouterView} from 'vue-router';
import HelloWorld from './components/HelloWorld.vue';
</script>

<template>
    <div class="container">
  <header>
      <svg>
        <use href="@/assets/sprites.svg#logo"></use>
      </svg>
      <nav>
        <ul>
          <li><RouterLink>Home</RouterLink></li>
          <li><RouterLink>Blog</RouterLink></li>
          <li><RouterLink>About Us</RouterLink></li>
          <li><RouterLink>Contact us</RouterLink></li>
        </ul>
        <button class="button_alternate">Subscribe</button>
      </nav>
  </header>
</div>

  <RouterView />
</template>

<style scoped lang="scss">
header {
  padding-top: 13px;
  padding-bottom: 12px;
  background-color: var(--black);
  color: var(--white);
  display: flex;
  justify-content: space-between;
  align-items: center;
  svg {
    width: 150px;
    height: 30px;
  }
}
nav {
  display: flex;
  gap: 31px;
}
ul {
  display: flex;
  gap: 27px;
  padding-top: 14px;
}
</style>
