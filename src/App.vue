<script setup></script>

<template>
  <header>
    <div class="header__content">
      <div class="header__links">
        <a href="">
          <img src="@/assets/img/location.svg" alt="Locations">
          <span>Krasnoyarks</span>
        </a>
        <a href="">Two</a>
      </div>
      <div class="header__phone">
        <a href="tel:+79082090500">79082090500</a>
      </div>
    </div>
  </header>


  
  <nav>
    <div class="nav__content"></div>
  </nav>
</template>

<style scoped>
header {
  background: #4d4d4d;
}
.header__content {
  max-width: calc(1920px - 192px - 192px);
  margin: 0 auto;
  padding: 0 8px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 44px;
}

/* .header__links a {
  margin-right: 12px;
}

.header__links a:last-child {
  margin-right: 0;
} */

.header__links {
  display: flex;
  align-items: center;
  gap: 12px;
}

.header__links a,
.header__phone a {
  color: white;
  text-decoration: none;
}

.header__links a {
  display: flex;
  align-items: center;
  gap: 4px;
}

/* nav */
nav {}

.nav__content {
  
}
</style>
