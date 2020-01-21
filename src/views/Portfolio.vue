<template>
  <div class="about">
    <h1>Portfólio</h1>
    <Footer :linkLeft="'/about'" :linkRight="'/contact'" />
  </div>
</template>

<script>
import Footer from '@/components/footer.vue'

export default {
  components: {
    Footer
  }
}
</script>
