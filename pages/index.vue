<template>
  <div>
    <lj-header curr="home" />
    
    <lj-footer />
  </div>
</template>

<script>
import LjHeader from '@/components/layout/header'
import LjFooter from '@/components/layout/footer'
// import Intro from '@/components/intro'
export default {
  components: {
    LjHeader,
    LjFooter, 
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