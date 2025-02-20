<template>
  <header>
    <div class="container">
      <div class="header__inner">
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
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
header {
  color: var(--white);
  .header__inner {
    padding: 13px 80px 12px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
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
