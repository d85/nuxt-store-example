<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/products">Products</NuxtLink>
        <ul>
        </ul>
      </nav>
    </header>

    <!-- output the page content -->
    <div>
      <slot />
    </div>
    <footer>
      <li>
        <NuxtLink to="/">Home</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/about">About</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/products">Products</NuxtLink>
      </li>
    </footer>
  </div>
</template>


<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>
