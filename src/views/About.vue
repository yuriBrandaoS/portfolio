<template>
  <div class="about">
    <h1>Sobre mim</h1>
    <Footer :linkRight="'/portfolio'" />
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
