<template>
  <!-- position: relative; -->
  <div>
    <lj-header curr="home" style />
    <!-- <div class="banner_text"></div> -->
    <div class="contain_serve w1320 mg-auto ly fl-c">
      <div class="contain_serve_title ly mg-auto">部署服务</div>
      <div class="contain_serve_child ly fl-r js-b ">
        <div class="contain_serve_child_text ly fl-c" style="border:1px green solid;">
          <div class="contain_top ly fl-c  w100" style="color:#fff;">
            <div class="contain_top_title w100">标准化部署服务</div>
            <div class="contain_top_text">快熟上手分秒资产管理，进去智能资产管理时代</div>
          </div>
          <ul style="padding:45px 45px 38px;box-sizing:border-box;">
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
        <div class="contain_serve_child_text ly fl-c" style="border:1px green solid;">
          <div class="contain_top ly fl-c w1320 brown" style="color:#fff;">
            <div class="contain_top_title w100">VIP个性化部署服务</div>
            <div class="contain_top_text">顾问式服务，打造企业专属管理方式</div>
          </div>
          <ul style="padding:45px 45px 38px;box-sizing:border-box;">
            <li class="ly fl-r al-c">
              <div class="circular  brown"></div>数字化工作方式讲解
            </li>
            <li class="ly fl-r al-c">
              <div class="circular brown"></div>分享同行优先管理模式，人才物事省钱提效方案
            </li>
            <li class="ly fl-r al-c">
              <div class="circular  brown"></div>分秒功能演示（六大模块演示）
            </li>
            <li class="ly fl-r al-c">
              <div class="circular  brown"></div>服务群在线培训
            </li>
            <li class="ly fl-r al-c">
              <div class="circular  brown"></div>实施搭建体验
            </li>
          </ul>
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