<script>
import Navigatoin from "@/components/Navigation.vue";
export default {
    name:'Header'    
}
</script>

<template>
    <header>
    <img
      alt="Vue logo"
      class="logo"
      src="@/assets/logo.svg"
      width="125"
      height="125"
    />    
    <Navigation />
  </header>
</template>


<style>
header{
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:15px;
}
</style>