<template>
  <!-- Main jumbotron for a primary marketing message or call to action
    -->
  <div class="container">
    <!-- Example row of columns -->
    <div class="row padtop">
      <div class="col-md-12">
        <h1>戰象系</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-12">
        <div class="spw">
          <em
            >這篇文章是將有關於戰象系裝甲的。而關於戰象單位這個兵種的資料請參見<nuxt-link
              to="/War_unitsanimal/Elephant"
              >波斯戰象</nuxt-link
            ></em
          >
        </div>
      </div>
      <div class="col-md-12">
        <div class="n1">
          <p>
            戰象系是一個防禦裝甲類別，所有在這個系列的兵種都會被剋戰象系的兵種有額外的傷害。
          </p>
        </div>
        <h3>戰象系單位</h3>
        <div class="hrn1"></div>
        <div class="n1">
          下列的單位都是戰象系單位
          <ul>
            <li>
              <img
                class="gg"
                src="~assets/Battleelephanticon.png"
                alt=""
              /><nuxt-link to="/units/Battle_Elephant">矛象伕</nuxt-link>→
              <img
                class="gg"
                src="~assets/Battleelephanticon.png"
                alt=""
              /><nuxt-link to="/units/Battle_Elephant">精銳矛象伕</nuxt-link>
            </li>
            <li>
              <img
                class="gg"
                src="~assets/WarElephantIcon.jpg"
                width="22"
                alt=""
              /><nuxt-link to="/War_unitsanimal/Elephant">波斯戰象</nuxt-link>→
              <img
                class="gg"
                src="~assets/WarElephantIcon.jpg"
                width="22"
                alt=""
              /><nuxt-link to="/War_unitsanimal/Elephant"
                >精銳波斯戰象</nuxt-link
              >(<nuxt-link to="/civs/Persians">波斯</nuxt-link>限定)
            </li>
            <li>
              <img
                class="gg"
                src="~assets/ElephantArcherIcon.jpg"
                alt=""
              /><nuxt-link to="/Elephant_units/Archer">象弓騎兵</nuxt-link>→
              <img
                class="gg"
                src="~assets/ElephantArcherIcon.jpg"
                alt=""
              /><nuxt-link to="/Elephant_units/Archer">精銳象弓騎兵</nuxt-link
              >(<nuxt-link to="/civs/Indians">印度</nuxt-link>限定)
            </li>
            <li>
              <img
                class="gg"
                src="~assets/Ballistaelephanticon.png"
                alt=""
              /><nuxt-link to="/Ballista_unitsanimal/Elephant">弩炮象</nuxt-link
              >(-2)→
              <img
                class="gg"
                src="~assets/Ballistaelephanticon.png"
                alt=""
              /><nuxt-link to="/Ballista_unitsanimal/Elephant"
                >精銳弩炮象</nuxt-link
              >(-2)(<nuxt-link to="/civs/Khmer">高棉</nuxt-link>限定)
            </li>
          </ul>
        </div>
        <h3>剋戰象系的單位與建築</h3>
        <div class="hrn1"></div>
        <div class="n1">
          以下單位擁有對戰象系的額外傷害，按照傷殺力排列。
          <div class="n1">
            <div class="col-md-12">
              <div class="col-md-4">
                <div style="margin:12px 0px;"><strong>+28攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/HalberdierIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Halberdier">戟兵</nuxt-link>
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+25攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/PikemanIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Pikeman">重裝長槍兵</nuxt-link>
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+20攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/Kamayuk_Icon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Kamayuk">槍隊長</nuxt-link>→
                    <img
                      class="gg"
                      src="~assets/Kamayuk_Icon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Kamayuk">精銳槍隊長</nuxt-link
                    >(<nuxt-link to="/civs/Incas">印加</nuxt-link>限定)
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+15攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/SpearmanIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Spearman">長槍兵</nuxt-link>
                  </li>
                </ul>
              </div>
              <div class="col-md-4">
                <div style="margin:12px 0px;"><strong>+8攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/HeavyScorpionIcon.jpg"
                      alt=""
                    /><nuxt-link to="/Heavyunits/Scorpion">重型弩炮</nuxt-link>
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+7攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/New_Genoese_Crossbowman.png"
                      alt=""
                    /><nuxt-link to="/Genoese_units/Crossbowman"
                      >精銳熱那亞弩手</nuxt-link
                    >(<nuxt-link to="/civs/Italians">義大利</nuxt-link>限定)
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+5攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/New_Genoese_Crossbowman.png"
                      alt=""
                    /><nuxt-link to="/Genoese_units/Crossbowman"
                      >熱那亞弩手</nuxt-link
                    >(<nuxt-link to="/civs/Italians">義大利</nuxt-link>限定)
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'alllarmor',
  components: {}
}
</script>
<style></style>
