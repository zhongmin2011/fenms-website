<template>
  <div>
    <lj-header curr="service" />

    <div style="height:700px;position: relative;">
      <img src="@/assets/images/case.png" alt style="width:100%;display:bolck" />
      <div class="bottom ly fl-r">
        <div class="bottom_row ly fl-c js-c">
          <a href="#service">
            <div class="bottom_title">部署服务</div>
          </a>
          <div class="bottom_text">组织需要快速上手分秒资产管理，专家根据具体情况，提供工作流程配置、全员培训、行业解决方案等服务。</div>
        </div>
        <div class="bottom_row ly fl-c js-c">
          <a href="#support">
            <div class="bottom_title">使用支持</div>
          </a>
          <div class="bottom_text">组织需要快速实时的解决产品使用问题，分秒资产管理提供热线、在线及自学习的使用手册，帮组组织快速解决疑问。</div>
        </div>
        <div class="bottom_row ly fl-c js-c">
          <a href="#consult">
            <div class="bottom_title">咨询定制</div>
          </a>
          <div class="bottom_text">分秒科技认证专家团队为组织提供量身定制服务，保障组织需求诊断到定制方案落地；服务期间7X24小时应急响应。</div>
        </div>
      </div>
    </div>

    <div class="contain_serve w1320 mg-auto ly fl-c">
      <div class="contain_serve_title ly mg-auto" id="service">部署服务</div>
      <div class="contain_serve_child ly fl-r js-b">
        <div class="contain_serve_child_text ly fl-c">
          <div class="contain_top ly fl-c w100">
            <div class="contain_top_title w100">标准化部署服务</div>
            <div class="contain_top_text">快熟上手分秒资产管理，进去智能资产管理时代</div>
          </div>
          <ul>
            <li class="ly fl-r al-c">
              <div class="circular"></div>数字化工作方式讲解
            </li>
            <li class="ly fl-r al-c">
              <div class="circular"></div>分享同行优先管理模式，人才物事省钱提效方案
            </li>
            <li class="ly fl-r al-c">
              <div class="circular"></div>分秒功能演示（六大模块演示）
            </li>
            <li class="ly fl-r al-c">
              <div class="circular"></div>服务群在线培训
            </li>
            <li class="ly fl-r al-c">
              <div class="circular"></div>实施搭建体验
            </li>
          </ul>
        </div>
        <div class="contain_serve_child_text ly fl-c">
          <div class="contain_top ly fl-c w1320" style="background-color:#CCB17D;">
            <div class="ly fl-r">
              <div class="contain_top_title w100">VIP个性化部署服务</div>
              <div class="contain_top_pay ly js-c al-c">付费</div>
            </div>

            <div class="contain_top_text">顾问式服务，打造企业专属管理方式</div>
          </div>
          <ul>
            <li class="ly fl-r al-c">
              <div class="circular_brown"></div>数字化工作方式讲解
            </li>
            <li class="ly fl-r al-c">
              <div class="circular_brown"></div>分享同行优先管理模式，人才物事省钱提效方案
            </li>
            <li class="ly fl-r al-c">
              <div class="circular_brown"></div>分秒功能演示（六大模块演示）
            </li>
            <li class="ly fl-r al-c">
              <div class="circular_brown"></div>服务群在线培训
            </li>
            <li class="ly fl-r al-c">
              <div class="circular_brown"></div>实施搭建体验
            </li>
          </ul>
        </div>
      </div>
    </div>

    <div class="support ly fl-c mg-auto">
      <div class="support_title mg-auto" id="support">分秒资产使用支持</div>
      <div class="support_bottom ly fl-r js-b">
        <div class="support_bottom_row ly fl-c">
          <div class="ly fl-r al-c js-c" style="height:32px;">
            <div>
              <img src="@/assets/images/tel.png" alt />
            </div>
            <div class="support_bottom_row_detail">热线服务</div>
          </div>
          <div
            class="support_bottom_row_center ly js-c al-c"
            style="border-left: 1px #707070 solid;"
          >0512-87819908</div>
          <div class="support_bottom_row_time ly js-c al-c">周一至周五 9：00-18:00</div>
        </div>
        <div class="support_bottom_row ly fl-c">
          <div class="ly fl-r al-c js-c" style="height:32px;">
            <div>
              <img src="@/assets/images/correct.png" alt />
            </div>
            <div class="support_bottom_row_detail">在线咨询</div>
          </div>
          <div class="support_bottom_row_center ly js-c al-c">
            <img src="@/assets/images/cord.png" alt />
          </div>
          <div class="support_bottom_row_time ly js-c al-c">钉钉扫码进入服务中心</div>
        </div>
        <div class="support_bottom_row ly fl-c">
          <div class="ly fl-r al-c js-c" style="height:32px;">
            <div>
              <img src="@/assets/images/correct.png" alt />
            </div>
            <div class="support_bottom_row_detail">产品使用手册</div>
          </div>
          <div class="support_bottom_row_center ly js-c al-c">
            <router-link to="help">
              <button>产品使用手册</button>
            </router-link>
          </div>
          <div class="support_bottom_row_time ly js-c al-c">点击查看手册</div>
        </div>
      </div>
    </div>

    <div class="consultation ly fl-c">
      <div class="consultation_title mg-auto" id="consult">分秒资产使用支持</div>
      <div class="consultation_bottom ly fl-r js-b">
        <div class="ly fl-c">
          <div class="consultation_img">
            <img src="@/assets/images/case_img.png" alt />
          </div>
          <div class="consultation_bottom_row_text ly fl-c">
            <div class="consultation_bottom_title">定制专属分秒</div>
            <div class="consultation_bottom_text">量身定制工作台皮肤与欢迎页，自定软件背景，提升员工归属感</div>
          </div>
        </div>
        <div class="ly fl-c">
          <div class="consultation_img">
            <img src="@/assets/images/case_img.png" alt />
          </div>
          <div class="consultation_bottom_row_text ly fl-c">
            <div class="consultation_bottom_title">专有云服务</div>
            <div class="consultation_bottom_text">为企业设立属于自己的独立数据服务器和机房，让企业数据与公有数据完全隔离，确保数据安全</div>
          </div>
        </div>
        <div class="ly fl-c">
          <div class="consultation_img">
            <img src="@/assets/images/case_img.png" alt />
          </div>
          <div class="consultation_bottom_row_text ly fl-c">
            <div class="consultation_bottom_title">云化咨询</div>
            <div class="consultation_bottom_text">当组织需要规划云上战略，分秒专家提供面向业务现状和发展目标的战略、分析、规划，帮助组织实现云化升级</div>
          </div>
        </div>
        <div class="ly fl-c">
          <div class="consultation_img">
            <img src="@/assets/images/case_img.png" alt />
          </div>
          <div class="consultation_bottom_row_text ly fl-c">
            <div class="consultation_bottom_title">系统集成服务</div>
            <div class="consultation_bottom_text">依托分秒专家技术团队，为企业统一资产管理，一个入口打通资产管理所有流程，资产有迹可寻</div>
          </div>
        </div>
      </div>
    </div>

    <div class="passageway ly fl-c">
      <div class="passageway_title mg-auto">预约服务快捷通道</div>
      <div class="passageway_bottom ly fl-r js-b">
        <img src="@/assets/images/passageway.png" alt />
      </div>
      <div class="passageway__infor ly fl-c js-c al-c">
        <router-link to="apply">
          <button>点击填写信息</button>
        </router-link>
        <div class="passageway__infor_text">先钉钉登入，在填写预约信息</div>
      </div>
    </div>

    <div class="service ly fl-c">
      <div class="service_title mg-auto">服务案例</div>
      <div class="service_bottom ly fl-r js-b">

        <div class="service_bottom_row" v-for="(item,index) in list" :key="index">
          <div class="service_row_top">
            <img src="@/assets/images/service_bg.png" alt />
            <div
              class="row_text"
            >{{item.des}}</div>
          </div>
          <div class="service_row_bootom ly fl-r">
              <div class="headImg"></div> 
              <div class="bottom_right ly fl-c">
                  <div class="service_row_title">{{item.name}}</div>
                  <div class="service_row_text ly fl-r">
                      <div>{{item.company}}</div>
                      <div style="margin-left:30px;">{{item.position}}</div>
                  </div>
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
import config from "@/config";

const detail = config.detail; // 文章详情的配置
export default {
  components: {
    LjHeader,
    LjFooter
  },
  data() {
    return {
      detail,
      list:[
        {
          des:'分秒资产管理系统专家帮我们根据我行业和我司业务特点，定制一趟资产管理解决方案，资产成本介绍30%，使用效率提高4倍，为我们业务做了重要支持。',
          name:'张某某',
          company:'苏州某某有限科技',
          position:'CEO' 
        },
         {
          des:'分秒资产管理系统专家帮我们根据我行业和我司业务特点，定制一趟资产管理解决方案，资产成本介绍30%，使用效率提高4倍，为我们业务做了重要支持。',
          name:'张某某',
          company:'苏州某某有限科技',
          position:'CEO' 
        },
         {
          des:'分秒资产管理系统专家帮我们根据我行业和我司业务特点，定制一趟资产管理解决方案，资产成本介绍30%，使用效率提高4倍，为我们业务做了重要支持。',
          name:'张某某',
          company:'苏州某某有限科技',
          position:'CEO' 
        },
      ]
    };
  },
  methods: {}
};
</script>

<style scoped src="./index.css"></style>