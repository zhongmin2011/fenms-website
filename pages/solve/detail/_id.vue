<template>
  <div class="solve_list">

    <div class="mian_contain_one ly fl-b js-b w50 mg-t40">
          <div class="ly fl-c js-c al-s fx-1 mian_contain_title">
            <div class="one_title">教育行业</div>
            <span style="margin-top:28px;">明确企业资产管理的目标、策略和管理制度等。</span>
          </div>
          <div class="tu_img"></div>
        </div>
        <div class="mian_contain_one ly fl-b js-b w50 mg-t40">
          <div class="tu_img"></div>
          <div class="ly fl-c js-c al-s fx-1 mian_contain_title">
            <div class="one_title">制造行业</div>
            <span style="margin-top:28px;">明确企业资产管理的角色和分工，包括行政、采购、财务、销售、IT部门等。</span>
          </div>
        </div>
        <div class="mian_contain_one ly fl-b js-b w50 mg-t40">
          <div class="ly fl-c js-c al-s fx-1 mian_contain_title">
            <div class="one_title">餐饮行业</div>
            <span style="margin-top:28px;">建立准确资产信息库包括与财务、合同、供应商、客户、监控等关联关系；优化管理流程；明确企业资产管理关键绩效。</span>
          </div>
          <div class="tu_img"></div>
        </div>
        <div class="mian_contain_one ly fl-b js-b w50">
          <div class="tu_img"></div>
          <div class="ly fl-c js-c al-s fx-1 mian_contain_title">
            <div class="on-tle">物业管理</div>
            <span style="margin-top:28px;">选择合适的企业资产管理平台而非管理软件；根据公司资产管理策略和制度，建立资产数据库、管理流程和资产报表等。</span>
          </div>
        </div>
        <div class="mian_contain_one ly fl-b js-b w50">
          <div class="ly fl-c js-c al-s fx-1 mian_contain_title">
            <div class="one_title">酒店行业</div>
            <span style="margin-top:28px;">明确企业资产管理的目标、策略和管理制度等。</span>
          </div>
          <div class="tu_img"></div>
        </div>
        <div class="mian_contain_one ly fl-b js-b w50 mg-t40">
          <div class="tu_img"></div>
          <div class="ly fl-c js-c al-s fx-1 mian_contain_title">
            <div class="one_title">互联网行业</div>
            <span style="margin-top:28px;">明确企业资产管理的角色和分工，包括行政、采购、财务、销售、IT部门等。</span>
          </div>
        </div>

   
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
      productList: config.productList,
    };
  },
  methods: {}
};
</script>
<style scoped src="./index.css"></style>