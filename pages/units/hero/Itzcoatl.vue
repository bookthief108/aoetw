<template>
  <!-- Main jumbotron for a primary marketing message or call to action
    -->
  <div class="container">
    <!-- Example row of columns -->
    <div class="row padtop">
      <div class="col-md-12">
        <h1>伊茲柯阿特爾</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            <strong>伊茲柯阿特爾</strong>是一名可在《世紀帝國II HD：
            非洲王朝》的地圖編輯器中使用的<nuxt-link to="/units/Infantry_Units"
              >步兵</nuxt-link
            >
            <nuxt-link to="/units/hero">英雄</nuxt-link
            >。他的原型是特諾奇提特蘭的第四代統治者，在位時間為1427/1428年到1440年，此時正是墨西加人推翻特帕內克人，並最終建立
            <nuxt-link to="/civs/Aztecs">阿茲特克</nuxt-link
            >帝國的時期。作為一個英雄單位，他無法被招降且會自動回血。
          </p>
          <p>
            在遊戲中，伊茲柯阿特爾以<nuxt-link to="/units/Jaguar_Warrior"
              >豹勇士</nuxt-link
            >的外表登場，但是能力更強。和其他步兵單位一樣，伊茲柯阿特爾會受到所有影響步兵的升級及加成影響。
          </p>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#d01022;">
              <div class="unititle">
                <nuxt-link to="">伊茲柯阿特爾</nuxt-link>
              </div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/JaguarWarriorIcon.jpg" width="80" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#d01022;">
              <div class="unititle2" style="color: #fff;">單位介紹</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">類型</td>
            <td class="unit4">
              <nuxt-link to="/units/Infantry_Units">步兵</nuxt-link>
              <br /><nuxt-link to="/units/hero">英雄</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">出場</td>
            <td class="unit4">非洲王朝</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#d01022;">
              <div class="unititle2" style="color: #fff;">數據</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">血量</td>
            <td class="unit4">300</td>
          </tr>
          <tr>
            <td class="unit3">攻擊</td>
            <td class="unit4">18(近戰)</td>
          </tr>
          <tr>
            <td class="unit3">攻擊速度</td>
            <td class="unit4">2.03</td>
          </tr>
          <tr>
            <td class="unit3">攻擊加成</td>
            <td class="unit4">
              對<nuxt-link to="/armor/Armor_Class_Infantry">步兵</nuxt-link> +15
              <br />對<nuxt-link to="/armor/Armor_Class_Eagle_Warrior"
                >鷹勇士</nuxt-link
              >
              +2 <br />對<nuxt-link to="/armor/Armor_Class_standard_building"
                >標準建築</nuxt-link
              >
              +4
            </td>
          </tr>
          <tr></tr>
          <tr></tr>
          <tr>
            <td class="unit3">近防</td>
            <td class="unit4">2</td>
          </tr>
          <tr></tr>
          <tr>
            <td class="unit3">遠防</td>
            <td class="unit4">1</td>
          </tr>
          <tr>
            <td class="unit3">防禦類型</td>
            <td class="unit4">
              <nuxt-link to="/armor/Armor_Class_Infantry">步兵</nuxt-link>
              <br /><nuxt-link to="/armor/Armor_Class_Unique_Unit"
                >特殊單位</nuxt-link
              >
            </td>
          </tr>
          <tr>
            <td class="unit3">跑速</td>
            <td class="unit4">1</td>
          </tr>
          <tr>
            <td class="unit3">視野</td>
            <td class="unit4">5</td>
          </tr>
        </table>

        <div class="thanks">感謝! 此頁面由Falcon6164協助編輯</div>
        <div class="wiki" style="margin-top: 5px;">
          <div style="float: left;">
            <img src="~assets/Wikipedia-logo.png" width="50" height="46" />
          </div>
          <div style="margin-left: 60px;">
            維基百科上的伊茲柯阿特爾
            <div style="margin-left: 10px;">
              <i
                ><strong
                  ><a
                    href="https://zh.wikipedia.org/wiki/%E4%BC%8A%E5%85%B9%E7%A7%91%E7%93%A6%E7%89%B9%E5%B0%94"
                    >伊茲柯阿特爾</a
                  ></strong
                ></i
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-12"></div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'allhero',
  components: {}
}
</script>
<style></style>
