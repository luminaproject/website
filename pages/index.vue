<template>
  <section class="app-container">
    <div class="flex justify-center flex-column vh-75 bg-light-blue">
      <Header
        class="pl4 mt6 lh-copy"
        text="High quality web technologies and operations meeting industry state of the art"
      />
      <Header class="pl4 mt5" text="Meet Lumina"/>
    </div>
    <div class="vh-75 flex flex-column justify-start bg-near-white bt bb gray">
      <div class="ph4 pt5 pb3 f2 fw7 mid-gray">What is Lumina about</div>
      <div class="w-25 mh4 bb mid-gray"></div>
      <p class="ph4 f2 mt4 lh-title black-80">{{ description }}</p>
    </div>
    <div class="vh-75 flex flex-column justify-start bg-near-white bb gray">
      <div class="ph4 pt5 pb3 f2 fw7 mid-gray">Contacts</div>
      <div class="w-25 mh4 bb mid-gray"></div>
      <div class="ph4 f2 mt4 black-80">Email: yadayada@gmail.com</div>
      <div class="ph4 f2 mt4 black-80">Number: +37499999999</div>
    </div>
  </section>
</template>

<script>
import Header from '~/components/Header.vue'

export default {
  data() {
    return {
      description: `
        Ether is built on a set of small core libraries.
        Their simplicity belies the fact that they are the
        outcome of years of building design systems across
        projects that range from marketing sites to enterprise
        applications. These libraries won’t try to do everything.
        They try to do the right thing.
      `
    }
  },
  components: {
    Header
  }
}
</script>

<style lang="scss">
@import 'node_modules/cepheus/sass/cepheus';
@import 'node_modules/normalize-scss/sass/normalize/import-now';
@import url('https://fonts.googleapis.com/css?family=Open+Sans');

.app-container {
  min-height: 100vh;
  font-family: 'Open Sans', serif;
}
</style>
