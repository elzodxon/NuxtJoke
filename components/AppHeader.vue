<template>
  <div>
    <b-navbar  variant="info">
      <b-navbar-brand href="#">jokes</b-navbar-brand>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <nuxt-link to="/">Home</nuxt-link>
          <nuxt-link to="/about">About</nuxt-link>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
name: "AppHeader"
}
</script>

<style scoped>

</style>
