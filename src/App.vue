<template>
  <section>
    <Pet />
  </section>
</template>

<script>
import Pet from './components/Pet.vue'


export default {
  name: 'App',
  components: { Pet }
}
</script>

<style lang="scss">
@import '@/assets/scss/app';

html {
  background: radial-gradient(50vmin 50vmin, #FEB4FF, #A3A3EC);
  background-repeat: no-repeat;
  background-color: #a3a3ec;
}

html, body {
  width: 100%;
  height: 100%;
  margin: 0;
  padding: 0;
  font-size: 14px;
}

*, *:before, *:after {
  box-sizing: border-box;
  position: relative;
}
</style>
