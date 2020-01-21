<template>
  <nav class="navbar fixed-bottom navbar-light bg-light">
    <router-link :to="linkLeft" class="float-left">
      <i class="fas fa-chevron-left fa-3x "></i>
    </router-link>
    <router-link :to="linkRight" :class="floatRight">
      <i class="fas fa-chevron-right fa-3x "></i>
    </router-link>
  </nav>
</template>

<script>

export default {
  props: {
    floatRight: {
      type: String
    },
    linkLeft: {
      type: String,
      default: '/'
    },
    linkRight: {
      type: String,
      default: '/'
    }
  }
}
</script>

<style scoped>
</style>
