<template>
  <!-- Main jumbotron for a primary marketing message or call to action
    -->
  <div class="container">
    <!-- Example row of columns -->
    <div class="row padtop">
      <div class="col-md-12">
        <h1>弓鋸</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            弓鋸是<nuxt-link to="/techs/age/Castle_Age">城堡時代</nuxt-link
            ><nuxt-link to="/building/Lumber_Camp">伐木場</nuxt-link
            >的科技，研發後可使村民收集木材的速度增快20%。一搬來說許可的話，建議一上城堡時代立即研發此科技，非常重要
          </p>
        </div>
        <h3>文明加成</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li><nuxt-link to="/civs/Burmese">緬甸</nuxt-link>:弓鋸免費。</li>
            <li>
              <nuxt-link to="/civs/Chinese">中國</nuxt-link
              >:科技在城堡/帝王時代各便宜15%/20%。
            </li>
          </ul>
        </div>
        <h3>歷史</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <em
            >"弓鋸有一個像弓一樣的圓形手柄，鋸片連接著弓端。使用弓鋸的伐木工能減少浪費並從每棵樹中獲得更多可用的木材。"</em
          >
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle"><nuxt-link to="">弓鋸</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/Bowsaw.jpg" width="45" alt="" />
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
            <td class="unit4">所有文明</td>
          </tr>
          <tr>
            <td class="unit3">時代</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/Castle-age-reseach.jpg"
                alt=""
              /><nuxt-link to="/techs/age/Castle_Age">城堡時代</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">訓練於</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/Lumbercampicon.png"
                alt=""
              /><nuxt-link to="/building/Lumber_Camp">伐木場</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">升級所需科技</td>
            <td class="unit4">
              <img class="gg" src="~assets/Doublebitaxe.jpg" alt="" /><nuxt-link
                to="/techs/Double-Bit_Axe"
                >雙刃斧</nuxt-link
              >
            </td>
          </tr>
          <tr>
            <td class="unit3">次一升級</td>
            <td class="unit4">
              <img class="gg" src="~assets/Twomansaw.jpg" alt="" /><nuxt-link
                to="/techs/Two-Man_Saw"
                >雙人鋸</nuxt-link
              >
            </td>
          </tr>
          <tr>
            <td class="unit3">訓練時間</td>
            <td class="unit4">50秒</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2"><nuxt-link to="">成本</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">食物</td>
            <td class="unit4">150</td>
          </tr>
          <tr>
            <td class="unit3">木</td>
            <td class="unit4">100</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2"><nuxt-link to="">影響</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">影響</td>
            <td class="unit4">使村民收集木材速度增加20%。</td>
          </tr>
        </table>
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
