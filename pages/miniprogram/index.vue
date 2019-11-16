<template>
  <div>
    <lj-header curr="home" />
    <div class="main">
      护理小程序
    </div>
    <lj-footer />
  </div>
</template>

<script>
import LjHeader from '@/components/layout/header'
import LjFooter from '@/components/layout/footer'
export default {
  components: {
    LjHeader,
    LjFooter
  },
  data() {
    return {

    }  
  },
  methods: {
    
  }
}
</script>

<style scoped src="./index.css"></style>