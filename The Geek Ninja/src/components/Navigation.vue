<template>
  <div class="wrapper">
    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav>
    <h1>Navigation code here</h1>
  </div>
</template>

<script>
import { RouterLink, RouterView } from "vue-router";
export default {
  name: "Navigatoin",
};
</script>
