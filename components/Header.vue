<template lang="html">
  <div class="f4 white">
    {{ text }}
  </div>
</template>

<script>
export default {
  data() {
    return {}
  },
  props: {
    text: {
      type: String,
      required: true
    }
  }
}
</script>

<style lang="css">
</style>
