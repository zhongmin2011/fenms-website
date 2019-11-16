<template>
  <div>
    <div class="container ly ly-j ly-m">
      <img
        class="container__logo"
        src="../../../assets/images/logo.png"
        alt
        style="display:block;width:104px;height:36px;"
      />
      <div class="ly fl-r">
        <div class="ly h100 al-c">
          <a
            href="javascript:void(0);"
            v-for="(item,i) in list"
            :key="i"
            class="header-title ly js-c al-c h100"
            :class="{'header-title-link': curr == item.highlightName}"
            @click="$router.push(item.path)"
          >{{item.name}}</a>
          <!--  -->
        </div>
        <div class="ly fl-r">
          <router-link to="login">
            <button class="ly js-c al-c blue white">登录</button>
          </router-link>
          <button class="ly js-c al-c">注册</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    curr: String
  },
  data() {
    return {
      list: [
        {
          highlightName: "home",
          name: "首页",
          path: "/"
        },
        {
          highlightName: "product",
          name: "产品",
          path: "/product"
        },
        {
          highlightName: "solve",
          name: "行业解决方案",
          path: "/solve"
        },
        {
          highlightName: "case",
          name: "客户案例",
          path: "/case"
        },
        {
          highlightName: "service",
          name: "服务",
          path: "/service"
        },
        {
          highlightName: "apply",
          name: "免费申请",
          path: "/apply"
        }
      ]
    };
  }, 
};
</script>
<style>
</style>
<style scoped>
.fx-1 {
  flex: 1;
}
.al-s {
  align-content: flex-start;
}
.w100 {
  width: 100%;
}
.fl-c {
  flex-direction: column;
}
.fl-r {
  flex-direction: row;
}
.al-c-c {
  align-content: center;
}
.js-c {
  justify-content: center;
}
.js-s {
  justify-content: flex-start;
}
.js-b {
  justify-content: space-between;
}
.swiper-slide {
  height: 680px;
  width: 100%;
}
.banner {
  width: 100%;
  height: 680px;
  background: rgb(100, 114, 128);
}
.h100 {
  height: 100%;
}
.white {
  color: #fff;
}
.blue {
  background-color: #3296fa;
}
button {
  width: 120px;
  height: 80px;
  padding: 0;
  background: none;
  border: 0;
  border-right: 1px rgb(224, 224, 224) solid;
}
.fl-r {
  flex-direction: row;
}
a {
  text-decoration: none;
}
.js-c {
  justify-content: center;
}
.al-c {
  align-items: center;
}
.container {
  height: 80px;
  width: 1440px;
}
.container__logo {
  width: 245px;
  height: 54px;
}
.header-title {
  margin-right: 20px;
  padding: 0 30px;
  height: 80px;
  font-size: 16px;
  font-family: PingFang SC;
  font-weight: 500;
  line-height: 18px;
  color: rgba(62, 62, 62, 1);
  box-sizing: border-box;
  /* border-bottom: 4px solid #3296FA; */
}
.header-title:last-child {
  margin-right: 0;
}

.header-title-link {
  border-bottom: 4px solid #3296fa;
}
</style>