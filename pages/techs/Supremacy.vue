<template>
  <!-- Main jumbotron for a primary marketing message or call to action
    -->
  <div class="container">
    <!-- Example row of columns -->
    <div class="row padtop">
      <div class="col-md-12">
        <h1>霸權</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            霸權是<nuxt-link to="/civs/Spanish">西班牙</nuxt-link
            >的特殊科技，可於<nuxt-link to="/techs/age/Imperial_Age"
              >帝王時代</nuxt-link
            >在
            <nuxt-link to="/building/Castle">城堡</nuxt-link
            >研發。研發後給<nuxt-link to="/units/Villager">村民</nuxt-link
            >+6攻擊、護甲+2/+2、HP+40。
          </p>
        </div>
        <h3>戰術要點</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              霸權不僅提高村民生命值，也給攻擊和護甲，讓他們能防衛<nuxt-link
                to="/units/Infantry_Units"
              ></nuxt-link
              >步兵和<nuxt-link to="/units/Light_Cavalry">輕騎兵</nuxt-link
              >的攻擊，也讓他們在前線修復或建造城堡、箭塔和城牆時能存活得更久。
            </li>
            <li>
              結合坑道工兵，村民可以在進攻中用來破壞敵人的建築物。這對電腦AI特別有效，因為如果他們的部隊在別處時他們經常忽略村民。但是要記住，研究霸權不會把村民變成正規的軍隊，所以在微操作上仍是困難的，因為他們不會自動攻擊敵人。
            </li>
            <li>
              在帝王時代早期，用村民作戰的優勢在於它立即提供了一支龐大的軍隊。但是，這會削弱玩家的經濟，所以他們應該衡量是否冒著失去很多村民的風險做進攻。無論如何，在帝王時代末期，村民們再也不能和敵方軍隊抗衡了。
            </li>
            <li>
              霸權通常被用來對付僧侶，主要是因為村民有足夠的力量殺死僧侶，而招降村民的舉動實際上跟招降<nuxt-link
                to="/units/Conquistador"
                >征服者</nuxt-link
              >和
              <nuxt-link to="/units/Paladin">遊俠</nuxt-link
              >等貴重單位比起來沒有什麼價值。
            </li>
            <li>
              霸權也與西班牙文明加成+
              30％的施工速度有很好的效果，因為村民在前線建設軍事設施時會受到攻擊，霸權他們能多承受一些敵軍的砲火並完成工作，使得西班牙的村民在遊戲中可說是最好也最強的。
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
              >能夠加速霸權的研究時間(快25%)。
            </li>
          </ul>
        </div>
        <h3>歷史</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <p>
            西班牙的農民在一個任何人都不容易生活的時代過著特別艱苦的生活，不同的是，西班牙是中世紀大部分地區的戰場，因為北部的基督教王國努力從八世紀入侵的薩拉森人手中重新奪回半島，因此西班牙農民也是部分時間的戰士。這也是拿破崙時期的法國軍隊在19世紀初學會的艱難不屈的生存之道。
          </p>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle"><nuxt-link to="">霸權</nuxt-link></div>
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
            <td class="unit4">
              <nuxt-link to="/civs/Spanish">西班牙</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">時代</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/Imperial-age-research.jpg"
                alt=""
              /><nuxt-link to="/techs/age/Imperial_Age">帝王時代</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">研發於</td>
            <td class="unit4">
              <img class="gg" src="~assets/Castleicon.png" alt="" /><nuxt-link
                to="/building/Castle"
                >城堡</nuxt-link
              >
            </td>
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
            <td class="unit4">400</td>
          </tr>
          <tr>
            <td class="unit3">黃金</td>
            <td class="unit4">250</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2"><nuxt-link to="">影響</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">影響</td>
            <td class="unit4">給村民+6攻擊、護甲+2/+2、HP+40。</td>
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
