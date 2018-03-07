<template>
  <div>
    <header>
      <nav class="flex w-75 justify-around f4 code pa1">
        <nuxt-link to="/" class="link underline-hover">Home</nuxt-link>
        <nuxt-link to="/new" class="link underline-hover">New</nuxt-link>
        <nuxt-link to="/show" class="link underline-hover">Show</nuxt-link>
        <nuxt-link to="/ask" class="link underline-hover">Ask</nuxt-link>
        <nuxt-link to="/jobs" class="link underline-hover">Jobs</nuxt-link>
      </nav>
    </header>
    <nuxt></nuxt>
  </div>
</template>

<script>
export default {

}
</script>

<style>
  .nuxt-link-exact-active {
    text-decoration: underline;
    font-weight: bold;
  }

</style>
