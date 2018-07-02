<template>
  <h1>Hello {{ name }}!</h1>
</template>
<script>

import 'vue-awesome/icons/trash'

import Icon from 'vue-awesome/components/Icon.vue'

export default {
  props: {
    name: {
      type: String,
      required: true
    }
  }
}
</script>


<style lang="stylus" scoped>
h1
  color red
</style>
