<template>
  <!-- Main jumbotron for a primary marketing message or call to action
    -->
  <div class="container">
    <!-- Example row of columns -->
    <div class="row padtop">
      <div class="col-md-12">
        <h1>城門</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            城門是世紀帝國II進入封建時代可以建造的防禦性建築，他可以建在城牆上，可以讓同盟通過同時阻擋敵人。
          </p>
          <p>當石牆升級成垛牆時，城門也會升級生命值從2700變成4000。</p>
          <p>
            城門除了哥德之外的所有文明都可以使用，垛牆和升級過的城門除了哥德、匈奴、馬札爾、馬來和波斯以外的文明都可以使用。
          </p>
          <p>
            城門在友方單位靠近時會自動開啟讓他們通過，並在門下沒有任何單位時(我方或敵方)關上。為了避免敵方單位尾隨友方單位進門後佔住城門變成防守漏洞，可以將城門鎖定(可再次解鎖)；然而阻擋敵方單位時我方單位也無法通過該城門。
          </p>
        </div>
        <h3>更多數據</h3>
        <div class="hrn1"></div>
        <div class="n1"></div>
        <table class="table-bordered" width="100%">
          <tr class="tta">
            <td class="unit" colspan="2" style="text-align: center;">
              <div class="unititle">劣勢與優勢</div>
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:30%">強勢(容易對抗)</td>
            <td class="tta4">無</td>
          </tr>
          <tr>
            <td class="tta1" style="width:30%">劣勢(不易對抗)</td>
            <td class="tta4">除了僧侶外的全部單位。</td>
          </tr>
          <tr class="tta">
            <td class="unit" colspan="2" style="text-align: center;">
              <div class="unititle2">升級</div>
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">生命值</td>
            <td class="tta4">
              <p>
                <img
                  src="~assets/CastleAgeUnique.png"
                  width="30"
                  alt=""
                /><nuxt-link to="/techs/Great_Wall">長城</nuxt-link>(+30%
                HP/中國限定)
              </p>
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">招降抵抗</td>
            <td class="tta4">
              <p>
                <img src="~assets/Faith.jpg" width="30" alt="" /><nuxt-link
                  to="/techs/Treadmill_Crane"
                  >踏輪起重機</nuxt-link
                >(+20%工作效率)
              </p>
            </td>
          </tr>
        </table>

        <h3>文明加成</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              <nuxt-link to="/civs/Byzantines">拜占庭</nuxt-link
              >：城門封建/城堡/帝王時代多20%/30%/40%的血量。
            </li>
            <li>
              <nuxt-link to="/civs/Chinese">中國</nuxt-link
              >：在城堡/帝王時代，城門的技術價格便宜15％/20％。
            </li>
            <li>
              <nuxt-link to="/civs/Koreans">韓國</nuxt-link>：城門建築速度快33%
            </li>
            <li>
              <nuxt-link to="/civs/Malians">馬利</nuxt-link>：城門造價便宜15%。
            </li>
            <li>
              <nuxt-link to="/civs/Spanish">西班牙</nuxt-link
              >：城門建築速度快30%。
            </li>
          </ul>
        </div>
        <h3>團隊加成</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              <nuxt-link to="/civs/Malians">馬利</nuxt-link
              >：研究踏輪起重機團隊速度提高80%。
            </li>
            <li><nuxt-link to="/civs/Mayans">馬雅</nuxt-link>：城門便宜50%</li>
          </ul>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle"><nuxt-link to="">城門</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/Palisadegateicon.png" width="45" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2"><nuxt-link to="">概要</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">類型</td>
            <td class="unit4">防禦建築</td>
          </tr>
          <tr>
            <td class="unit3">文明</td>
            <td class="unit4">除了哥德以外的所有文明</td>
          </tr>
          <tr>
            <td class="unit3">時代</td>
            <td class="unit4">封建時代</td>
          </tr>
          <tr>
            <td class="unit3">使用</td>
            <td class="unit4">防止敵方單位進入，讓友方單位通過</td>
          </tr>
          <tr>
            <td class="unit3">建築時間</td>
            <td class="unit4">30秒</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2"><nuxt-link to="">成本</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">石材</td>
            <td class="unit4">30</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2"><nuxt-link to="">數據</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">尺寸</td>
            <td class="unit4">4x1</td>
          </tr>
          <tr>
            <td class="unit3">血量</td>
            <td class="unit4">
              封建時代1375 <br />城堡時代2750/4000(升級)
              <br />帝王時代2750/4000(升級)
            </td>
          </tr>
          <tr>
            <td class="unit3">近戰護甲</td>
            <td class="unit4">6</td>
          </tr>
          <tr>
            <td class="unit3">遠程護甲</td>
            <td class="unit4">6</td>
          </tr>
          <tr>
            <td class="unit3">護甲分類</td>
            <td class="unit4">
              建築(+20) <br />標準建築 <br />石造防禦 <br />城門和城牆
            </td>
          </tr>
          <tr>
            <td class="unit3">視野</td>
            <td class="unit4">6</td>
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
  layout: 'allbuilding',
  components: {}
}
</script>
<style></style>
