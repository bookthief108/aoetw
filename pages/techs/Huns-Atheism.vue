<template>
  <!-- Main jumbotron for a primary marketing message or call to action
    -->
  <div class="container">
    <!-- Example row of columns -->
    <div class="row padtop">
      <div class="col-md-12">
        <h1>無神論</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            無神論是匈奴的特殊科技，可於帝王時代在城堡研發。研發後世界奇觀、遺跡倒數時間增加100年，間諜/叛國者科技便宜50%。
          </p>
        </div>
        <h3>戰術要點</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>無神論的效果會影響所有玩家而非只有研發科技的玩家本身。</li>
            <li>
              研發無神論的時機是看遊戲的進展，而且如果是死鬥模式那無神論便一無是處。如果勝利條件為"世界奇觀"或"遺跡"，額外的一百年搭配匈奴人對建築物的攻擊加成讓敵方玩家看到匈奴人時都會頭痛不已。
            </li>
            <li>
              另外間諜/叛國者科技便宜50%可讓匈奴人以較低的花費監視敵方動向。其他文明則因為成本過高通常都不會研發該科技(每個敵隊村民耗費200黃金)
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
              >能夠加速無神論的研究時間(快25%)。
            </li>
          </ul>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle"><nuxt-link to="">無神論</nuxt-link></div>
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
            <td class="unit4">匈奴</td>
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
            <td class="unit4">60秒</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2"><nuxt-link to="">成本</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">食物</td>
            <td class="unit4">500</td>
          </tr>
          <tr>
            <td class="unit3">黃金</td>
            <td class="unit4">500</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2"><nuxt-link to="">影響</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">影響</td>
            <td class="unit4">
              世界奇觀、遺跡倒數時間增加100年，間諜/叛國者科技便宜50%。
            </td>
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
