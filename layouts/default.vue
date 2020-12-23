<template>
  <div>
    <AppHeader/>
    <Nuxt />
    <AppFooter/>
  </div>
</template>

<style>
</style>
<script>
import AppHeader from "../components/AppHeader";
import AppFooter from "../components/AppFooter";
export default {
  components: {AppFooter, AppHeader}
}
</script>
