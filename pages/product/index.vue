<template>
  <div>
    <lj-header curr="product" />

    <slider animation="fade" style="height:680px;">
      <slider-item
        v-for="(i, index) in Urimg"
        :key="index"
        @click="hello"
        :style="{background:'url('+i.img+')'}"
      >
        <div class="ly ly-middle slide__main">
          <div class="slide__main__content w-100 ly lyd-c ly-middle">
            <img src="@/assets/images/ding.png" alt style="display: block;" />

            <div class="slide__main__content__title">分秒资产已入驻钉钉</div>
            <div
              class="slide__main__content__des ta-c"
            >分秒科技以精准数据及智慧监控助力企业资产管理，全链路支持企业成本管控，助力企业资产完成移动化、数据化、智慧化管理。</div>
            <div class="slide__main__content__btn ly fl-r">
              <router-link to="login">
                <button style="color: #3296FA;background:#fff;">注册新企业</button>
              </router-link>
              <router-link to="apply">
                <button>预约演示</button>
              </router-link>
            </div>
          </div>
        </div>
      </slider-item>
    </slider>

    <div class="product__content mg-auto w-100">
      <div class="ly lyd-c ly-c w-100">
        <div class="ly lyd-c ly-c al-c">
          <div class="ly lyd-c ly-c al-c">
            <div class="product__content__title ta-c">智能化资产管理-行业解决方案</div>
            <span class="product__content__des ta-c">分布的行业包括：教育、制造业、餐饮、物业、酒店、互联网等众多行业。</span>
          </div>
          <div class="mg-t45 w1400" style="background-color:#44AFFB;height:600px;">
            <img src alt />
          </div>
        </div>

        <div v-for="(item,index) in productList" :key="index" class="product__item">
          <div class="product__content__row ly ly-j w-50" v-if="(index+1)%2==1">
            <div class="ly lyd-c ly-c al-s fx-1 product__content__row__right">
              <div class="product__content__title">{{item.name}}</div>
              <span class="product__content__des" style="margin-top:28px;">{{item.des}}</span>
            </div>
            <div class="tu_img"></div>
          </div>

          <div class="product__content__row ly ly-j w-50" v-else>
            <div class="tu_img"></div>
            <div class="ly lyd-c ly-c al-s fx-1 product__content__row__right">
              <div class="product__content__title">{{item.name}}</div>
              <span class="product__content__des" style="margin-top:28px;">{{item.des}}</span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="sys__content ly lyd-c">
      <div class="ly lyd-c mg-auto">
        <div class="sys__content__title ta-c">系统功能模块-贯穿资产全生命</div>
        <span class="sys__content__des ta-c">理清资产管理的目标和思路 明确流程和方法 建立全流程资产管理平台</span>
      </div>
      <img src="@/assets/images/sys.png" alt style="margin-top:60px;" />
    </div>

    <div class="advantage__content ly lyd-c">
      <div class="ly lyd-c mg-auto">
        <div class="advantage__content__title">产品解决用户痛点-智能化资产管理</div>
        <span class="advantage__content__des">理清资产管理的目标和思路 明确流程和方法 建立全流程资产管理平台</span>
      </div>
      <div class=" ly ly-j mg-t60">
        <div class="advantage__content__row ly lyd-c">
          <div class="ly ly-c ly-middle">
            <img src="@/assets/images/solve1.png" alt />
          </div>
          <div class="advantage__content__row__text ly lyd-c f-l">
            <div class="advantage__contain__row__text__title mg-auto">资产模块全面管理</div>
            <div class="advantage__contain__row__text_des ta-c">
              ·资产采购管理 ·资产流程管理
              <br />·资产财务管理 ·资产台账管理
              <br />·资产盘点管理 ·资产分析管理
              <br />让资产管理更系统！
            </div>
          </div>
        </div>
        <div class="advantage__content__row ly lyd-c">
          <div class="ly ly-c ly-middle">
            <img src="@/assets/images/solve2.png" alt />
          </div>
          <div class="advantage__content__row__text ly lyd-c f-l">
            <div class="advantage__contain__row__text__title mg-auto">资产专家在线指导</div>
            <div class="advantage__contain__row__text_des">
              固定资产管理专家在线进行业
              务指导以及实施培训，让业务
              咨询更便捷！！
            </div>
          </div>
        </div>
        <div class="advantage__content__row ly lyd-c">
          <div class="ly ly-c ly-middle">
            <img src="@/assets/images/solve3.png" alt />
          </div>
          <div class="advantage__content__row__text ly lyd-c f-l">
            <div class="advantage__contain__row__text__title mg-auto">IT运维服务</div>
            <div class="advantage__contain__row__text_des">
              专业团队上门服务，解决办公
              资产盘点难、周期长等问题
              全国上门服务
              提前预约次日上门。
            </div>
          </div>
        </div>
        <div class="advantage__content__row ly lyd-c">
          <div class="ly ly-c ly-middle">
            <img src="@/assets/images/solve4.png" alt />
          </div>
          <div class="advantage__content__row__text ly lyd-c f-l">
            <div class="advantage__contain__row__text__title mg-auto">资产模块全面管理</div>
            <div class="advantage__contain__row__text_des">
              针对客户业务需求定制开发，
              满足企业个性化需求。
            </div>
          </div>
        </div>
      </div>
      <div class="advantage__btn ly fl-r ly-middle mg-auto">
        <router-link to="login">
          <button style="color: #3296FA;background:#fff;">注册使用</button>
        </router-link>
        <router-link to="apply">
          <button>预约演示</button>
        </router-link>
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
      images: [img1, img2, img3, img4],
      Urimg: [
        {
          img: img1,
          title1: "分秒资产已入驻钉钉分秒资产已入驻钉钉",
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
      // console.log(`hello index: ${$event}`)
    }
  }
};
</script>

<style scoped src="./index.css"></style>

