<template>
  <div id="app">
    <div class="container">
      <div id="nav">
        <router-link to="/about">About me</router-link>
        <router-link to="/">Home</router-link>

      </div>
      <transition name="fade">
        <router-view/>
      </transition>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style>
#app {
  font-family: 'Roboto Condensed', sans-serif;
  text-align: center;
  color: #2c3e50;
  height: 2vh;
  width: 80%;
  box-sizing: border-box;
  position: relative;
  margin: 0;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  margin-left: 10%;
  font-size: 18px;
  float: right;
}

#nav a.router-link-exact-active {
  color: #3273A0;
}

.fade-enter-active, .fade-leave-active {
  transition-property: opacity;
  transition-duration: .39s;
}

.fade-enter-active {
  transition-delay: .39s;
}

.fade-enter, .fade-leave-active {
  opacity: 0
}
</style>
