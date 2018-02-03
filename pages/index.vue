<template>
  <section class="container">
    <div class="header-container">
      <div class="pt5 pl3">
        <Header text="Meet Lumina"/>
        <Header text="Lorem Ipsum dolor sit amet bhbashdbhasd bhasbdasn ahsbd cbahsdb"/>
      </div>
    </div>
  </section>
</template>

<script>
import Header from '~/components/Header.vue'

export default {
  components: {
    Header
  }
}
</script>

<style lang="scss" scoped>
@import '../node_modules/cepheus/sass/cepheus';
@import 'node_modules/normalize-scss/sass/normalize/import-now';
@import url('https://fonts.googleapis.com/css?family=Open+Sans');

.container {
  min-height: 100vh;
  font-family: 'Open Sans', serif;
  .header-container {
    height: 100vh;
    background: url('https://i.imgur.com/azFkTZb.jpg');
    background-repeat: no-repeat;
    background-size: contain;
  }
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
