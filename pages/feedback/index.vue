<template>
  <div>
    <lj-header curr="home" /> 
    <div class="apply_contain">
      <div class="apply_contain_bg ly fl-c">
        <div class="apply_contain_title">问题反馈，为您提供更好的服务</div>
        <div class="apply_contain_row ly fl-c">
          <div
            class="apply_contain_row_text"
          >分秒资产管理系统于钉钉协作，借助成型的组织架构和优秀的生态布局，架构资产管理瓶体啊，帮助企业完成资产管理，灵活用于外部采购管理、内部流转管理、成本数据把控、多维度数据分析、跨部门协同等资产管理场景，已向数家企业输出实践方案。我们很乐意与您所在的企业分享经验，并提供免费演示方案。</div>

          <div class="apply_contain_input ly fl-c">
            <div class="row_text">
              <span>*</span>您的名字
            </div>
            <div class="row_text">希望我们如何称呼您？</div>
            <input type="text" class="input_text" placeholder="您的名字" />
          </div>

          <div class="apply_contain_input ly fl-c">
            <div class="row_text">
              <span>*</span>手机
            </div>
            <div class="row_text">资产顾问将在1-2个工作日内致电您。</div>
            <input type="text" class="input_text" placeholder="您的手机号码" />
          </div>

          <div class="apply_contain_input ly fl-c">
            <div class="row_text">
              <span>*</span>企业名称
            </div>
            <div class="row_text">提前了解您的业务特征，更好的为您提供解决方案。</div>
            <input type="text" class="input_text" placeholder="您的企业名称" />
          </div>

          <div class="apply_contain_input ly fl-c">
            <div class="row_text">
              <span>*</span>预期使用规模
            </div>
            <div class="row_text">企业使用人数，资产规模，方便提供服务方式。</div>
            <textarea name="" id="" cols="30" rows="10" placeholder="您的使用规模"></textarea>
            <!-- <input type="text" class="input_text"  /> -->
          </div>

           <div class="apply_contain_input ly fl-c">
            <div class="row_text">
              <span>*</span>咨询内容描述
            </div>
            <div class="row_text">简要的说明你的问题，示例：价格方案/上门演示/私有部署/专项服务等。</div>
            <textarea name="" id="" cols="30" rows="10" placeholder="您的咨询内容描述"></textarea>
            <!-- <input type="text" class="input_text"  /> -->
          </div>

          <div class="bottom_button ly js-c">
            <button>提交填写内容</button>
          </div>
          

         
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