<template>
  <div>
    <lj-header curr="home" />
    <div class="contain ly fl-c">
      <div class="contain_main ly fl-c js-c al-c">
        <div class="contain_main_top ly fl-r">
          <div class="line"></div>
          <div class="datail">EVERY ENTERPRISE NEEDS TO MANAGE ASSETS</div>
        </div>
        <div class="contain_main_title">分秒资产定价及VIP服务</div>
        <div class="contain_main_text">
          分秒资产管理系统服务模块针对客户拥有资产条目数目进行分级收费
          <br />提供专业的增项VIP服务，满足客户个性化需求
        </div>
      </div>

      <div class="contain_bottom ly js-a fl-r">
        <div class="contain_bottom_row ly fl-c">
          <div class="row_text ly fl-c">
            <div class="row_title">专业版</div>
            <div class="row_dateil">适用于任何规模团队或企业</div>
          </div>
          <div class="row_contain ly fl-c">
            <div class="row_pice ly fl-c">
              <div class="ly fl-r">
                <div class="price_icon">￥</div>
                <div class="price_title">{{priceMajor}}</div>
                <div class="price_text">元/年</div>
              </div>
              <!-- <input type="text" /> -->
              <select
                class="row_select"
                name="item.value"
                v-model="selected"
                @change="changeValue(selected)"
              >
                <option
                  :value="item.id"
                  class="select_option"
                  v-for="(item,i) in priceList"
                  :key="i"
                >{{item.value}}</option>
              </select>

              <button>注册使用</button>
              <div class="price_detail">免费预约顾问演示</div>
            </div>

            <div class="row_contain_text">
              <div class="row_contain_text_datail">资产管理系统专业版功能包含以下内容：</div>
              <ul>
                <li class="ly fl-r">
                  <div class="circular"></div>资产概况模块（资产数据量化表达）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产采购模块（采购申请/审核/退货等）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产流程模块（领用/借用/转移/维护等）
                </li>
                <li class="opacity25 ly fl-r">
                  <div class="circular"></div>资产销售模块（资产销售流程全程掌控）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产财务模块（财务付款/退款/记录/冲销等）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产台账模块（资产多维度查询等）
                </li>

                <li class="ly fl-r">
                  <div class="circular"></div>资产分析模块（资产数据分析报表等）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产盘点模块（年/季/月/日盘点资产稽核）
                </li>
                <li class="opacity25 ly fl-r">
                  <div class="circular"></div>资产监控模块（资产位置查询，定期巡检等）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>系统管理模块（权限/客户/流程管控等）
                </li>
              </ul>
            </div>
            <div class="row_contain_text">
              <div class="row_contain_text_datail">基本服务：</div>
              <div class="ly fl-r row_contain_text_datail_li">
                <div class="circular"></div>资产概况模块（资产数据量化表达）
              </div>
              <div class="row_contain_text_datail" style="margin-top: 10px;">企业增值服务：</div>
              <ul>
                <li class="ly fl-r">
                  <div class="circular"></div>现场实施服务（费用另计）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>远程实施服务（费用另计）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>系统现场培训（费用另计）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>个性化定制（费用另计）
                </li>
              </ul>
            </div>
          </div>
        </div>

        <div class="contain_bottom_row ly fl-c">
          <div class="row_text ly fl-c">
            <div class="row_title">企业版</div>
            <div class="row_dateil">适用于专业资产管理、成本管控等</div>
          </div>
          <div class="row_contain ly fl-c">
            <div class="row_pice ly fl-c">
              <div class="ly fl-r" style="borrder:1px red solid;">
                <div class="price_icon">￥</div>
                <div class="price_title">{{pricecompany}}</div>
                <div class="price_text">元/年</div>
              </div>
              <!-- <input type="text" /> -->
               <select
                class="row_select"
                name="item.value"
                v-model="selected2"
                @change="changeValue2(selected2)"
              >
                <option
                  :value="item.id"
                  class="select_option"
                  v-for="(item,i) in priceListCompany"
                  :key="i"
                >{{item.value}}</option>
              </select>
              <button>注册使用</button>
              <div class="price_detail">免费预约顾问演示</div>
            </div>

            <div class="row_contain_text">
              <div class="row_contain_text_datail">资产管理系统专业版功能包含以下内容：</div>
              <ul>
                <li class="ly fl-r">
                  <div class="circular"></div>资产概况模块（资产数据量化表达）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产采购模块（采购申请/审核/退货等）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产流程模块（领用/借用/转移/维护等）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产销售模块（资产销售流程全程掌控）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产财务模块（财务付款/退款/记录/冲销等）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产台账模块（资产多维度查询等）
                </li>

                <li class="ly fl-r">
                  <div class="circular"></div>资产分析模块（资产数据分析报表等）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产盘点模块（年/季/月/日盘点资产稽核）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产监控模块（资产位置查询，定期巡检等）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>系统管理模块（权限/客户/流程管控等）
                </li>
              </ul>
            </div>
            <div class="row_contain_text">
              <div class="row_contain_text_datail">基本服务：</div>
              <div class="ly fl-r row_contain_text_datail_li">
                <div class="circular"></div>资产概况模块（资产数据量化表达）
              </div>
              <div class="row_contain_text_datail" style="margin-top: 10px;">企业增值服务：</div>
              <ul>
                <li class="ly fl-r">
                  <div class="circular"></div>现场实施服务（费用另计）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>远程实施服务（费用另计）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>系统现场培训（费用另计）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>个性化定制（费用另计）
                </li>
              </ul>
            </div>
          </div>
        </div>

        <div class="contain_bottom_row ly fl-c">
          <div class="row_text ly fl-c">
            <div class="row_title">私有部署版</div>
            <div class="row_dateil">适合于本地私有化部署</div>
          </div>
          <div class="row_contain ly fl-c">
            <div class="row_pice ly fl-c">
              <div class="ly fl-r" style="borrder:1px red solid;">
                <div class="price_title" style="line-height:80px;">价格面议</div>
                <!-- <div class="price_icon">￥</div>
                <div class="price_title">3999</div>
                <div class="price_text">元/年</div>-->
              </div>
              <input type="text"  class="row_input" value="不限资产条目"/>
              <button>注册使用</button>
              <div class="price_detail">免费预约顾问演示</div>
            </div>

            <div class="row_contain_text">
              <div class="row_contain_text_datail">资产管理系统专业版功能包含以下内容：</div>
              <ul>
                <li class="ly fl-r">
                  <div class="circular"></div>资产概况模块（资产数据量化表达）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产采购模块（采购申请/审核/退货等）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产流程模块（领用/借用/转移/维护等）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产销售模块（资产销售流程全程掌控）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产财务模块（财务付款/退款/记录/冲销等）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产台账模块（资产多维度查询等）
                </li>

                <li class="ly fl-r">
                  <div class="circular"></div>资产分析模块（资产数据分析报表等）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产盘点模块（年/季/月/日盘点资产稽核）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>资产监控模块（资产位置查询，定期巡检等）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>系统管理模块（权限/客户/流程管控等）
                </li>
              </ul>
            </div>
            <div class="row_contain_text">
              <div class="row_contain_text_datail">基本服务：</div>
              <div class="ly fl-r row_contain_text_datail_li">
                <div class="circular"></div>资产概况模块（资产数据量化表达）
              </div>
              <div class="row_contain_text_datail" style="margin-top: 10px;">企业增值服务：</div>
              <ul>
                <li class="ly fl-r">
                  <div class="circular"></div>现场实施服务（费用另计）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>远程实施服务（费用另计）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>系统现场培训（费用另计）
                </li>
                <li class="ly fl-r">
                  <div class="circular"></div>个性化定制（费用另计）
                </li>
              </ul>
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
export default {
  components: {
    LjHeader,
    LjFooter
  },
  data() {
    return {
      input: "",
      priceMajor: 2499,
      pricecompany:3999,
      selected: 1,
      selected2:1,
      priceList: [
        {
          id: "1",
          value: "0-1000条资产",
          price: "2499"
        },
        {
          id: "2",
          value: "1001-3000条资产",
          price: "4499"
        },
        {
          id: "3",
          value: "3001-6000条资产",
          price: "7499"
        },
        {
          id: "4",
          value: "6001-10000条资产",
          price: "10499"
        },
        {
          id: "5",
          value: "不限条数",
          price: "29999"
        }
      ],
      priceListCompany: [
        {
          id: "1",
          value: "0-1000条资产",
          price: "3999"
        },
        {
          id: "2",
          value: "1001-3000条资产",
          price: "7999"
        },
        {
          id: "3",
          value: "3001-6000条资产",
          price: "13999"
        },
        {
          id: "4",
          value: "6001-10000条资产",
          price: "19999"
        },
        {
          id: "5",
          value: "不限条数",
          price: "39999"
        }
      ]
    };
  },
  methods: {
    changeValue(value) { 
      this.priceMajor = this.priceList[value - 1].price;
    },
    changeValue2(value){
      this.pricecompany = this.priceListCompany[value - 1].price;
    }
  }
};
</script>
<style scoped src="./index.css"></style>