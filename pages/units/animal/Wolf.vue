<template>
  <!-- Main jumbotron for a primary marketing message or call to action
    -->
  <div class="container">
    <!-- Example row of columns -->
    <div class="row padtop">
      <div class="col-md-12">
        <h1>狼</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>狼是遊戲內的一種野生動物。</p>
          <p>
            狼是最常見會攻擊人的野生動物，牠有25的生命值與3的攻擊，沒有食物，牠可以咬死沒有織布的村民。
          </p>
          <p>
            <nuxt-link to="/Ornlu_the_Wolf">灰狼歐魯</nuxt-link
            >是狼的英雄，有20個攻擊與400的生命值。
          </p>
          <p>遊戲難易度會影響狼的視野，最簡單的是遊戲是6，中等與困難的是12。</p>
          <p>馬扎爾的村民可以一擊殺狼。</p>
          <img src="~assets/AoE2_wolf.png" alt="" />
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#b086b5;">
              <div class="unititle">
                <nuxt-link to="">科摩多巨蜥</nuxt-link>
              </div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/Wolf-icon-aoe2.jpg" width="80" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#b086b5;">
              <div class="unititle2" style="color: #fff;">單位介紹</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">食物量</td>
            <td class="unit4">0</td>
          </tr>
          <tr>
            <td class="unit3">血量</td>
            <td class="unit4">25</td>
          </tr>
        </table>

        <div class="thanks">感謝! 此頁面由眠協助編輯</div>
        <div class="wiki" style="margin-top: 5px;">
          <div style="float: left;">
            <img src="~assets/Wikipedia-logo.png" width="50" height="46" />
          </div>
          <div style="margin-left: 60px;">
            維基百科上的狼
            <div style="margin-left: 10px;">
              <i
                ><b><a href="http://tinyurl.com/y9thg6vb">狼</a></b></i
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'allanimal',
  components: {}
}
</script>
<style></style>
