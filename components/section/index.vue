<template>
  <div class="section">
    <label class="section__title">{{title}}</label>
    <slot></slot>
  </div>
</template>

<script>
export default {
  props: {
    title: String,
  },
  data() {
    return {
    }
  },
  methods: {

  }
}
</script>
<style scoped>
  .section {
    width: 1440px;
    margin: 60px auto;
  }

  .section__title {
    margin-bottom: 20px;
    font-size: 40px;
    font-weight: 600;
    color: #444444;
  }
</style>