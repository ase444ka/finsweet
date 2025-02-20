<script setup></script>

<template>
  <div class="cover">
    <div class="container">
      <div class="cover__inner">
        <figure class="cover__img">
          <img src="@/assets/images/man-in-black.png" />
        </figure>
        <div class="cover__subtitle">Posted on <a href="#">startup</a></div>
        <h2 class="cover__title display">
          Step-by-step guide to choosing great font pairs
        </h2>
        <div class="cover__info">
          By <a href="#">James West</a
          ><time datetime="2022-05-23">May 23, 2022</time>
        </div>
        <p class="cover__text">
          Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
          dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
          proident.
        </p>
        <button class="cover__button">Read More ></button>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.cover {
  color: var(--white);
  &__inner {
    position: relative;
    overflow: hidden;
    height: 720px;
    padding: 123px 80px;
  }
  &__img {
    position: absolute;
    display: block;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    z-index: -10;
    &::before {
      content: '';
      z-index: -1;
      width: 100%;
      height: 100%;
      display: block;
      position: absolute;
      z-index: 10;
      background: radial-gradient(
        30.56% 76.04% at 74.58% 0%,
        rgba(0, 0, 0, 0) 0%,
        rgba(0, 0, 0, 0.6) 100%
      );
    }
  }
  &__subtitle {
    text-transform: uppercase;
    letter-spacing: 2.9px;
    a {
      font-weight: 600;
      font-size: 0.95em;
      letter-spacing: 4.4px;
    }
  }
  &__title {
    padding-top: 21px;
    width: 70%;
  }
  &__info {
    padding-top: 24px;
    time {
      border-left: 1px solid var(--white);
      margin-left: 14px;
      padding-left: 10px;
      letter-spacing: 0.5px;
    }
  }
  &__title {
    padding-top: 19px;
  }
  &__text {
    padding-top: 16px;
    width: 45%;
    letter-spacing: 0.33px;
  }
  &__button {
    margin-top: 48px;
    margin-left: -2px;
  }
}
</style>
