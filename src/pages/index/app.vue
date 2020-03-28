<template>
  <div id="app">
    <div class="index-card">{{msg}}</div>
  </div>
</template>

<script>
import modal from '../../components/modal.vue'
export default {
  components: {
    modal
  },
  data() {
    return {
      msg: 'Use Vue 2.0 Today!'
    }
  },
  methods: {}
}
</script>

<style lang="postcss">
.index-card {
  width: 300px;
  margin: 10px auto;
  font-size: 30px;
}
</style>
