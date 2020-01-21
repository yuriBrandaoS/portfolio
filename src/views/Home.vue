<template>
  <div class="home">
    <div class="titles">
      <div class="titles-width">
        <h1 class="display-2 text-md-left">Yuri Brandão</h1>
        <h2 class="display-6 text-md-left">Web Developer</h2>
      </div>
        <img class="img-banner" alt="img-portfolio" src="../assets/code.svg">
    </div>
    <Footer :showArrowRight="true" :linkLeft="'/about'" :linkRight="'/about'" />
  </div>
</template>

<script>
import Footer from '@/components/footer.vue'

export default {
  name: 'home',
  components: {
    Footer
  }
}
</script>

<style scoped>
  .home {
    width: 100%;
    height: 0vh;
  }
  .titles {
    margin-top: 6%;
    text-align: center;
    font-family: 'Roboto Condensed', sans-serif;
  }

  .titles-width {
    max-width: 600px;
    margin: auto;
  }

  .img-banner {
    width: 35%;
    margin-left: 120px;

  }

</style>
