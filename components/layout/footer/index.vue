<template>
  <div class="footer">
    <div class="footer__item ly ly-j ly-m">
      <div class="footer__item-title h100 ly fl-c al-a">
        <div class="footer__item_top">
          <label class="footer__item-company">分秒科技发展有限公司</label>
          <div class="footer__item-address">
            江苏省苏州市姑苏区宝带西路1177号
            <br />世茂广场H幢3406室
          </div>
        </div>
        <div class="footer__item_bottom">
          <div class="public_text">
            Copyright © 2019-2022 Fenms
            苏 ICP 备 88888888 号-8
          </div>
          <div class="ly fl-r al-c mg-t5">
            <img src="@/assets/images/public.png" alt="">
            <div style="margin-left:10px;">苏公网安备  88888888888888号</div>
          </div>
          
        </div>
      </div>
      <div class="ly ly-j ly-m footer__item-content-menu">
        <div class="footer__item-menu h100">
          <label class="footer__item-menu-title">公司</label>
          <div class=" ly fl-c">
            <router-link to="about"><span> 关于我们</span></router-link>
            <span>加入我们</span>
            <span>合作伙伴</span>
          </div>
        </div>
        <div class="footer__item-menu h100">
          <label class="footer__item-menu-title">产品</label>
          <div class=" ly fl-c">
            <router-link to="product" class="span_router"><span>分秒资产</span></router-link>
            <router-link to="solve" class="span_router"><span>解决方案</span></router-link>
            <router-link to="update" class="span_router"><span style="font-size:16px;">最近更新</span></router-link>
            <router-link to="price" class="span_router"><span>价格</span></router-link>
          </div>
        </div>
        <div class="footer__item-menu" style="height:100%;">
          <label class="footer__item-menu-title">服务</label>
          <div class=" ly fl-c">
            <router-link to="help" class="span_router"><span style="font-size:16px;">帮助手册</span></router-link>
            <router-link to="feedback" class="span_router"><span>问题反馈</span></router-link>
          </div>
        </div>
        <div class="footer__item-menu"  style="height:100%;">
          <label class="footer__item-menu-title">合作</label>
          <div class=" ly fl-c">
            <router-link to="service_footer" class="span_router"><span>服务协议</span></router-link>
            <router-link to="agreement" class="span_router"><span style="font-size:16px;">隐私协议</span></router-link>
            <router-link to="channel" class="span_router"> <span>渠道合作</span></router-link>
          </div>
        </div>
      </div>
      <div class="footer__item-content ly h100">
        <div class="ta-r">
          <a class="footer__item-orderPhone" href="javascript:void(0);">服务热线</a>
          <div class="footer__item-Phone">0512-87819908</div>
          <div class="footer__item-time">周一至周五 9:00-18:00</div>
        </div>
        <img class="footer__item-orcode" src="./images/orcode.png" alt />
      </div>
    </div>
    
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  methods: {}
};
</script>
<style src="./style.css">
</style>
<style scoped></style>