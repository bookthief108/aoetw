<template>
  <!-- Main jumbotron for a primary marketing message or call to action
    -->
  <div class="container">
    <!-- Example row of columns -->
    <div class="row padtop">
      <div class="col-md-12">
        <h1>羅馬士兵</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            羅馬士兵出現在《世紀帝國II:失落的帝國》版本中的幾場戰役，也能在地圖編輯器找到。羅馬士兵
            不能被訓練，根據數據顯示其與精銳豹勇士的戰鬥力不相上下，只有遠程護甲與速度有差。
          </p>
        </div>
       
        
    
        <h3>圖庫</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <div class="col-md-12">
            <div class="col-md-4">
              <nuxt-link to="/img/Champion.png"
                ><img
                  class="imgn hg"
                  width="250"
                  src="~assets/Legionary.png"
                  alt=""
              /></nuxt-link>
              <p><em>一群羅馬士兵。</em></p>
            </div>
            <div class="col-md-4">
              <nuxt-link to="/img/Militialine.png"
                ><img
                  class="imgn hg"
                  width="250"
                  src="~assets/Roman_Legionary.jpg"
                  alt=""
              /></nuxt-link>
              <p><em>美術家對西元1世紀中到3世紀的羅馬士兵描繪圖。</em></p>
            </div>
            <div class="col-md-4">
              <nuxt-link to="/img/Militialine.png"
                ><img
                  class="imgn hg"
                  width="250"
                  src="~assets/LateRomanLegionary.jpg"
                  alt=""
              /></nuxt-link>
              <p><em>扮演西元5世紀羅馬士兵的表演家。</em></p>
            </div>
            
          </div>
        </div>
        </div>
 
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle"><nuxt-link to="">羅馬士兵</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/Legionaryicon.png" width="45" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2">
                <nuxt-link to="">單位介紹</nuxt-link>
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit3">類型</td>
            <td class="unit4">
              <nuxt-link to="/units/Infantry_Units">步兵</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">首次出現</td>
            <td class="unit4">
              <nuxt-link to="/techs/games/aof">失落的帝國</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2">數據</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">血量</td>
            <td class="unit4">75</td>
          </tr>
          <tr>
            <td class="unit3">攻擊</td>
            <td class="unit4">12</td>
          </tr>
          <tr>
            <td class="unit3">攻擊加成</td>
            <td class="unit4">
              +2對<nuxt-link to="/armor/Armor_Class_Eagle_Warrior"
                >鷹勇士</nuxt-link
              >
              <br />+10對<nuxt-link to="/armor/Armor_Class_Infantry"
                >步兵</nuxt-link
              >
              <br />+10對<nuxt-link to="/armor/Armor_Class_Standard_Condottiero"
                >傭兵</nuxt-link
              >
              <br />+2對<nuxt-link to="/armor/Armor_Class_Standard_Building"
                >標準建築</nuxt-link
              >
            </td>
          </tr>
          <tr>
            <td class="unit3">攻擊速度</td>
            <td class="unit4">2.03</td>
          </tr>
          <tr>
            <td class="unit3">近防</td>
            <td class="unit4">2</td>
          </tr>
          <tr>
            <td class="unit3">遠防</td>
            <td class="unit4">2</td>
          </tr>
          <tr>
            <td class="unit3">防禦</td>
            <td class="unit4">
              <nuxt-link to="/armor/Armor_Class_Infantry"></nuxt-link>步兵
            </td>
          </tr>
          <tr>
            <td class="unit3">跑速</td>
            <td class="unit4">0.9</td>
          </tr>
          <tr>
            <td class="unit3">視野</td>
            <td class="unit4">5</td>
          </tr>
        </table>

        <div class="thanks">感謝! 此頁面由賜齡協助編輯</div>
      </div>
   

</template>
<script>
export default {
  layout: 'allunit',
  components: {}
}
</script>
<style></style>
