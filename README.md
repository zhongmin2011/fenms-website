# 寅汇健康管理官网
## 业务梳理
* 页面
    * 首页
    * 服务方案
      * 列表。 读配置。
      * 详情页。
        * 左侧： 是列表里所有的服务(读配置)。 点击右侧内容会变
        * 内容：读个大配置的 js。根据内容去
    * 服务流程
    * 我的订单
    * 护理小程序
  * 组件
    * 布局
      * 顶部菜单
        * 当前高亮
      * 底部
    * 页面级别
      * 头部介绍(intro)。 首页，服务方案类
      * 内容块(section)。
        * props: 标题
        * slot 内容
  * CSS
    * .container 居中的主体宽度