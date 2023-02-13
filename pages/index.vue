<template>
  <div class="container">
    <h1>Home Page</h1>
    <p>
      Lorem test home
    </p>
    <img src="/images/nuxt.png" style="width: 200px" alt=""/>
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'Home page title',
  meta: [
    {name: 'description', content: 'home description site.'}
  ]
})
</script>

<style scoped>

</style>