<template>
  <!-- Main jumbotron for a primary marketing message or call to action
    -->
  <div class="container">
    <!-- Example row of columns -->
    <div class="row padtop">
      <div class="col-md-12">
        <h1>獨輪推車</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            獨輪推車可於<nuxt-link to="/techs/age/Feudal_Age"
              >封建時代</nuxt-link
            >在<nuxt-link to="/building/Town_Center">城鎮中心</nuxt-link
            >研發。研發後村民移動速度快10%，每趟可攜帶資源量+25%(從10增加為13，所以實際是30%)。
          </p>
          <p>
            獨輪推車通常是研發一級木與一級田之後才會研發，他將為每個村民增加7～13％的工作效率，但需要175食物50木頭與75秒的研究時間。當你有大約35個村民的時候最好研究這個技術，如果你不愛算村民數，那麼你在遊戲中，如果保持村民不間斷，大概是17～19分鐘時研發最好。還有一點，你有很多農夫時，可以更早研發，相反的，你在海圖靠捕魚或是很少農夫種田，那麼你可以晚點研發。
          </p>
          <p>當然如果打一般封快，上城堡前會先研發，這是高手間的習慣。</p>
        </div>
        <h3>文明加成</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              <nuxt-link to="/civs/Chinese">中國</nuxt-link
              >：該科技在封建/城堡/帝王時代花費便宜10%/15%/20%。
            </li>
            <li>
              <nuxt-link to="/civs/Persians">波斯</nuxt-link
              >：研究該科技的時間在封建/城堡/帝王時代快10%/15%/20%。
            </li>
            <li>
              <nuxt-link to="/civs/Vikings">維京</nuxt-link>：該科技免費。
            </li>
          </ul>
        </div>
        <h3>歷史</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <p>
            當大多數人在農業社區工作時，簡單的手推車或單輪手推車是一項重大發明。中世紀早期的工業很少。經濟主要靠種植農作物，放牧，收集和建設。獨輪車提供了重要的生產力改進。
          </p>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle"><nuxt-link to="">獨輪推車</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/Wheelbarrow.jpg" width="45" alt="" />
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
                src="~assets/Feudal-age-reseach.jpg"
                alt=""
              /><nuxt-link to="/techs/age/Feudal_Age">封建時代</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">研發於</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/Town-center-logo.jpg"
                alt=""
              /><nuxt-link to="/building/Town_Center">城鎮中心</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">可升級</td>
            <td class="unit4">
              <img class="gg" src="~assets/Handcart.jpg" alt="" /><nuxt-link
                to="/techs/Handcart"
                >手推車</nuxt-link
              >
            </td>
          </tr>
          <tr>
            <td class="unit3">訓練時間</td>
            <td class="unit4">75秒</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2"><nuxt-link to="">成本</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">食物</td>
            <td class="unit4">175</td>
          </tr>
          <tr>
            <td class="unit3">木材</td>
            <td class="unit4">50</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#31b0d5;">
              <div class="unititle2"><nuxt-link to="">影響</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">影響</td>
            <td class="unit4">村民移動速度快10%，每趟可攜帶資源量+25%。</td>
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
