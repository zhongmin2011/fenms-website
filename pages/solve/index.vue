<template>
  <div>
    <lj-header curr="solve" />

    <slider
      animation="fade"
      style="height:680px;background-image:url(./assets/images/banner1.png);"
    >
      <slider-item
        v-for="(i, index) in Urimg"
        :key="index"
        @click="hello"
        :style="{background:'url('+i.img+')'}"
      >
        <div class="ly js-s al-c main">
          <div class="main_text">
            <div class="ly js-s fl-r" style="height:20px;">
              <div class="line"></div>
              <div class="en_text">EVERY ENTERPRISE NEEDS TO MANAGE ASSETS</div>
            </div>
            <div class="title">
              <div>
                {{i.title1}}
                <br />
                {{i.title2}}
              </div>
            </div>
            <div class="text">{{i.text}}</div>
          </div>
        </div>
      </slider-item>
    </slider>

    <div class="mian_contain mg-auto w1400">
      <div class="mian_title">
        <div class="ly fl-c js-c al-c">
          <div class="ly fl-c js-c al-c">
            <div class="title_mian">智能化资产管理-行业解决方案</div>
            <span>分布的行业包括：教育、制造业、餐饮、物业、酒店、互联网等众多行业。</span>
          </div>
          <div style="margin-top:60px;background-color:#44AFFB;width:1400px;height:600px;">
            <img src alt />
          </div>
        </div>

        <div v-for="(item,index) in productList" :key="index" 
        @click="$router.push('/solve/detail/product_' + item.id)" class="solve__item">
         

          <div
            class="mian_contain_one ly fl-b js-b w50"
            v-if="(index+1)%2==1" 
          >
            <div class="ly fl-c js-c al-s fx-1 mian_contain_title">
              <div class="one_title">{{item.name}}</div>
              <span style="margin-top:28px;">{{item.des}}</span>
            </div>
            <div class="tu_img"></div>
          </div>

          <div class="mian_contain_one ly fl-b js-b w50" v-else >
            <div class="tu_img"></div>
            <div class="ly fl-c js-c al-s fx-1 mian_contain_title">
              <div class="one_title">{{item.name}}</div>
              <span style="margin-top:28px;">{{item.des}}</span>
            </div>
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
import { Slider, SliderItem } from "vue-easy-slider";
export default {
  components: {
    LjHeader,
    LjFooter,
    Slider,
    SliderItem 
  },
  data() {
    const img1 = require("@/assets/images/banner1.png");
    const img2 = require("@/assets/images/banner1.png");
    const img3 = require("@/assets/images/banner1.png");
    const img4 = require("@/assets/images/banner1.png");
    return {
      Urimg: [
        {
          img: img1,
          title1: "钉钉合作",
          title2: "资产全生命周期管理平台",
          text:
            " 分秒科技以精准数据及智慧监控助力企业资产管理，全链路支持企业成本管控，助力企业资产完成移动化、数据化、智慧化管理。"
        },
        {
          img: img2,
          title1: "分秒资产管理",
          title2: "行业解决方案",
          text:
            " 针对各行业务特性，打造以人为本、数据驱动的专业行业解决方案，为各行业提供新工作方式。"
        },
        {
          img: img3,
          title1: "七分甜餐饮管理",
          title2: "杯装杨枝甘露创造者",
          text:
            " 分秒科技为七分甜餐饮管理提供资产管理服务，结合餐饮管理模式提供优质数字化资产服务。"
        }
      ],
      productList: [
        {
          id: 1,
          name: "教育行业",
          des: "明确企业资产管理的目标、策略和管理制度等。"
        },
        {
          id: 2,
          name: "制造行业",
          des:
            "明确企业资产管理的角色和分工，包括行政、采购、财务、销售、IT部门等。"
        },
        {
          id: 3,
          name: "餐饮行业",
          des:
            "建立准确资产信息库包括与财务、合同、供应商、客户、监控等关联关系；优化管理流程；明确企业资产管理关键绩效。"
        },
        {
          id: 4,
          name: "物业管理",
          des:
            "选择合适的企业资产管理平台而非管理软件；根据公司资产管理策略和制度，建立资产数据库、管理流程和资产报表等。"
        },
        {
          id: 5,
          name: "酒店行业",
          des: "明确企业资产管理的目标、策略和管理制度等。"
        },
        {
          id: 6,
          name: "互联网行业",
          des:
            "明确企业资产管理的角色和分工，包括行政、采购、财务、销售、IT部门等。"
        }
      ]
    };
  },
  methods: {
    hello($event) {
      console.log($event, "$event");
    }
  }
};
</script>

<style scoped src="./index.css"></style>

