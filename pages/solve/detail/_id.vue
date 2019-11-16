<template>
  <div class="solve_list">   
    <div style="margin-top:20px"></div>

    <div style="color:red;">{{productDetail[index]}}</div>
  </div>
</template>

<script>
import LjHeader from "@/components/layout/header";
import LjFooter from "@/components/layout/footer";
import config from "@/config/index";

export default {
  components: {
    LjHeader,
    LjFooter,
    config
  },
  data() {
    return {
      index: null,
      productDetail: config.productDetail
    };
  },
  mounted() {
    var paramArr = this.$route.params.id.split("_");
    this.index = paramArr[1];
  },
  methods: {}
};
</script>
<style scoped src="./index.css"></style>