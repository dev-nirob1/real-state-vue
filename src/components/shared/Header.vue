<script setup lang="ts">
import { RouterLink } from 'vue-router';

</script>

<template>
  <header>
    <nav class="container flex justify-between align-center text-light">
      <figure>
        <img src="./../../assets/logo-header.png" alt="logo">
      </figure>
      <div class="hamburger">
        <span class="material-symbols-outlined">
          menu
        </span>
      </div>
      <!-- nav items  -->
      <ul class="nav">
        <li>
          <RouterLink to="/">Home</RouterLink>
        </li>
        <li>
          <RouterLink to="/about">About</RouterLink>
        </li>
        <li>
        <li class="header-dropdown">
          <a href="#">Project</a>
          <ul class="dropdown-menu">
            <li><a href="/projects">On Going</a></li>
            <li><a href="/projects">Completed</a></li>
            <li><a href="/projects">UpComing</a></li>
          </ul>
        </li>
        </li>
        <li>
          <RouterLink to="/gallery">Gallary</RouterLink>
        </li>
        <li>
          <RouterLink to="/contact">Contact</RouterLink>
        </li>
        <li>
          <RouterLink to="/details">Details</RouterLink>
        </li>
      </ul>
    </nav>
  </header>
  <!-- header ends here  -->
</template>

<style scoped>
header {
  background-color: var(--secondary-color);
  font-family: var(--popins-font);
  box-shadow: var(--header-shadow);
  /* padding: var(--header-padding); */
}

header nav {
  padding: 1rem 0;
}

header nav ul li:not(:last-child) {
  margin-right: 1rem;
}

header nav ul li a {
  padding: 1rem .8rem;
  font-size: 1.125rem;
  font-weight: 500;
}

header nav ul li a:hover {
  color: var(--primary-color);
  transition: all .3s ease-in-out;
}

.header-dropdown {
  position: relative;
}

.header-dropdown .dropdown-menu {
  border-top: 2px solid var(--primary-color);
  position: absolute;
  top: 40px;
  background-color: var(--secondary-color);
  width: 200px;
  opacity: 0;
  visibility: hidden;
  transform: translateY(15px);
  transition: opacity 0.3s ease, visibility 0.3s ease, transform 0.3s ease;
  z-index: 999;
}

.header-dropdown:hover .dropdown-menu {
  opacity: 1;
  visibility: visible;
  transform: translateY(0);
}

.dropdown-menu a {
  display: block;
  padding: .5rem 1rem;
}

.nav {
  display: none;
}

.hamburger {
  display: block;
}
@media (min-width: 992px) {
  .nav {
      display: flex;
  }

  .hamburger {
      display: none;
  }
}
</style>