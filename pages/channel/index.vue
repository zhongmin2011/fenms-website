<template>
  <div>
    <lj-header curr="home" />
    <div class="contain ly js-c">
      <div class="contain_main ly fl-c js-c al-c">
        <div class="contain_main_top ly fl-r">
          <div class="line"></div>
          <div class="datail">EVERY ENTERPRISE NEEDS TO MANAGE ASSETS</div>
        </div>
        <div class="contain_main_title">合作渠道</div>
        <div class="contain_main_text">
          请提交您的问题，根据问题安排合适的相关专家与您联系<br>
          （包括开发、资产管理、运维等方向）
        </div>
      </div>
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