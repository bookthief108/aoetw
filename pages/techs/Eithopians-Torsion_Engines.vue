<template>
  <!-- Main jumbotron for a primary marketing message or call to action
    -->
  <div class="container">
    <!-- Example row of columns -->
    <div class="row padtop">
      <div class="col-md-12">
        <h1>扭力彈射器</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            扭力彈射器是衣索比亞的特殊科技，可於帝王時代在城堡研發。研發後攻城單位的攻擊波及範圍增加。攻城塔和輕型衝撞車不受影響；裝甲和重型衝撞車受該科技影響。
          </p>
          <p>
            此科技配合衣索比亞的重型投石車，在狹窄的地圖如:黑森林將會非常地具有威脅性。
          </p>
        </div>
        <h3>戰術要點</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              扭力彈射器可讓投石車的波及範圍變大，彌補原本的準度不足造成的傷害下降。攻擊地面的指令可以擊中更多敵方單位，讓技術型的玩家能一擊摧毀一大群騎兵、弓箭手、分散的步兵或是數台的攻城武器。火炮也受益於扭力彈射器而能更好的反制攻城武器和弓箭手。
            </li>
          </ul>
        </div>
        <h3>團隊加成</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              <nuxt-link to="/civs/Berbers">柏柏</nuxt-link>：<nuxt-link
                to="/techs/Kasbah"
                >聚居堡壘</nuxt-link
              >能夠加速扭力彈射器的研究時間(快25%)。
            </li>
          </ul>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle">
                <nuxt-link to="">扭力彈射器</nuxt-link>
              </div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/Unique-tech.jpg" width="45" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2">
                <nuxt-link to="">科技介紹</nuxt-link>
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit3">文明</td>
            <td class="unit4">衣索比亞</td>
          </tr>
          <tr>
            <td class="unit3">時代</td>
            <td class="unit4">帝王時代</td>
          </tr>
          <tr>
            <td class="unit3">研發於</td>
            <td class="unit4">城堡</td>
          </tr>
          <tr>
            <td class="unit3">研發時間</td>
            <td class="unit4">40秒</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2"><nuxt-link to="">成本</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">食物</td>
            <td class="unit4">1000</td>
          </tr>
          <tr>
            <td class="unit3">黃金</td>
            <td class="unit4">600</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2"><nuxt-link to="">影響</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">影響</td>
            <td class="unit4">攻城單位的攻擊波及範圍增加。</td>
          </tr>
        </table>

        <div class="thanks">感謝! 此頁面由賜齡協助編輯</div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-12"></div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'alltech',
  components: {}
}
</script>
<style></style>
