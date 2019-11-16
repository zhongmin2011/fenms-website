<template>
  <div>
    <div class="container ly ly-j js-b al-c">
      <img
        class="container__logo"
        src="@/assets/images/logo.png"
        alt
        style="display:block;width:104px;height:36px;"
      />
      <button>注册</button>
    </div>

    <div class="login ly js-c al-c">
      <img src="@/assets/images/fenms.png" alt />
    </div>

    <lj-footer />
  </div>
</template>

<script>
import LjHeader from "@/components/layout/header";
import LjFooter from "@/components/layout/footer";
export default {
  components: {
    LjHeader,
    LjFooter
  },
  data() {
    return {};
  },
  methods: {}
};
</script>
<style scoped src="./index.css"></style>