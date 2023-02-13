<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container ">
        <NuxtLink to="/" class="navbar-brand">Test Nuxt</NuxtLink>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <NuxtLink to="/about" class="nav-link" aria-current="page">About</NuxtLink>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <slot/>
  </div>
</template>

<script>
export default {
  name: "default"
}
</script>

<style scoped>

</style>