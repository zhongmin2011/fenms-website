<template>
  <div>
    <lj-header curr="home" />
    <div class="banner" style="background-color: #fff; ">
      <div class="ly js-b al-c fl-r main">
        <div class="main_text">
          <div class="ly js-s fl-r" style="height:20px;">
            <div class="line"></div>
            <div class="en_text">EVERY ENTERPRISE NEEDS TO MANAGE ASSETS</div>
          </div>
          <div class="title">
            <div>
              分秒与钉钉合作
              <br />加入分秒资产管理交流群
            </div>
          </div>
          <div class="text">
            分秒科技以精准数据及智慧监控助力企业资产管理，全链路支持企业
            成本管控，助力企业资产完成移动化、数据化、智慧化管理
          </div>
        </div>
        <img src="@/assets/images/fenms.png" alt />
      </div>
    </div>

    <div class="introduce mg-auto">
      <div class="ly fl-c">
        <div class="introduce_title mg-auto">公司简介</div>
        <div class="introduce_contain ly fl-w">
          <div class="introduce_contain_row ly fl-c">
            <div class="introduce_contain_row_title ly fl-c">
              <div class="introduce_contain_row_top ly fl-r">
                <div class="introduce_contain_row_top_box ly js-c al-c">01</div>
                <div class="introduce_contain_row_top_title">发展的方向</div>
              </div>
              <div
                class="introduce_contain_row_bottom"
              >我们坚持以客户为中心，为客户提供智能化资产管理平台，以保证客户资产的有效管理，公司以产品为中心，不断的提升产品体验，为客户提供优质的服务。</div>
            </div>
          </div>

          <div class="introduce_contain_row ly fl-c">
            <div class="introduce_contain_row_title ly fl-c">
              <div class="introduce_contain_row_top ly fl-r">
                <div class="introduce_contain_row_top_box ly js-c al-c">02</div>
                <div class="introduce_contain_row_top_title">战略的目标</div>
              </div>
              <div
                class="introduce_contain_row_bottom"
              >我们要实现和改善公司影响力、市场地位和竞争能力，扩大我们的业务领域和范围、增强我们的研发储备、提高我们的服务水平，提升客户的体验及满意度。</div>
            </div>
          </div>

          <div class="introduce_contain_row ly fl-c">
            <div class="introduce_contain_row_title ly fl-c">
              <div class="introduce_contain_row_top ly fl-r">
                <div class="introduce_contain_row_top_box ly js-c al-c">03</div>
                <div class="introduce_contain_row_top_title">企业的使命</div>
              </div>
              <div
                class="introduce_contain_row_bottom"
              >为客户的利益而努力提高我们的专业储备和服务水平，帮我们的客户提高工作效率，成为最杰出的公司，为成为中国最好的资产管理软件平台而时刻努力。</div>
            </div>
          </div>

          <div class="introduce_contain_row ly fl-c">
            <div class="introduce_contain_row_title ly fl-c">
              <div class="introduce_contain_row_top ly fl-r">
                <div class="introduce_contain_row_top_box ly js-c al-c">04</div>
                <div class="introduce_contain_row_top_title">我们的愿景</div>
              </div>
              <div
                class="introduce_contain_row_bottom"
              >为我们的员工、管理人员、股东创造实现美好理想的机会，为我们的客户提供优质的服务，为社会创造价值。分秒科技，珍惜身边的每一分每一秒。</div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="experience ly fl-c">
      <div class="experience_title mg-auto">公司简介</div>
      <!-- <img src="@/assets/images/experience.png" alt="" class="experience_img mg-auto" style="display:block;"> -->
      <div class="experience_contain ly fl-c">
        <div class="experience_contain_row ly fl-r">
          <div class="experience_contain_row_sno">2014年</div>
          <div class="circular_contain">
            <div class="circular"></div>
          </div>
          <div class="experience_contain_right ly fl-c">
            <div class="experience_contain_right_title">初出茅庐</div>
            <div class="experience_contain_right_text">分秒科技于2014年11月26日正式成立，现注册资金1100万。</div>
          </div>
        </div>
        <div class="experience_contain_row ly fl-r">
          <div class="experience_contain_row_sno">2015年</div>
          <div class="circular_contain">
            <div class="circular"></div>
          </div>
          <div class="experience_contain_right ly fl-c">
            <div class="experience_contain_right_title">快速发展</div>
            <div
              class="experience_contain_right_text"
            >分秒科技完成第一版本针对客户定制化开发的资产管理软件，在公司运营第一年完成3000万销售额的可喜业绩。</div>
          </div>
        </div>
        <div class="experience_contain_row ly fl-r">
          <div class="experience_contain_row_sno">2017年</div>
          <div class="circular_contain">
            <div class="circular"></div>
          </div>
          <div class="experience_contain_right ly fl-c">
            <div class="experience_contain_right_title">稳步成长</div>
            <div class="experience_contain_right_text">分秒科技形成了以资产管理软件为核心业务的稳步发展思路。分秒科技,珍惜您的每一分每一秒。</div>
          </div>
        </div>
        <div class="experience_contain_row ly fl-r">
          <div class="experience_contain_row_sno">2019年</div>
          <div class="circular_contain">
            <div class="circular"></div>
          </div>
          <div class="experience_contain_right ly fl-c">
            <div class="experience_contain_right_title">迎来挑战</div>
            <div
              class="experience_contain_right_text"
            >分秒科技在快速发展阶段,不断遇到来自于内部、外部的各方面挑战,积累了大量的业务、管理、技术、研发经验。</div>
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