<template>
  <!-- Main jumbotron for a primary marketing message or call to action
    -->
  <div class="container">
    <!-- Example row of columns -->
    <div class="row padtop">
      <div class="col-md-12">
        <h1>熱那亞弩手</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            熱那亞弩手是<nuxt-link to="/games/aof">失落的帝國</nuxt-link
            >資料片中義大利的特殊單位，能夠在<nuxt-link
              to="/techs/age/Castle_Age"
              >城堡時代</nuxt-link
            >的
            <nuxt-link to="/building/Castle">城堡</nuxt-link
            >中訓練。是個對騎兵有攻擊加成的弓兵。
          </p>
          <p>
            熱那亞弩手可以在<nuxt-link to="/techs/age/Imperial_Age"
              >帝王時代</nuxt-link
            >升級為精銳熱那亞弩手。
          </p>
        </div>
        <h3>戰術要點</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              熱那亞弩手是一個能對付騎兵的弓箭手。即使是強大的大象單位（如<nuxt-link
                to="/War_unitsanimal/Elephant"
                >戰象</nuxt-link
              >和<nuxt-link to="/Ballista_unitsanimal/Elephant"
                >矛象伕</nuxt-link
              >）在面對大量熱那亞弩手的時候也毫無招架之力，不過在面對
              <nuxt-link to="/civs/Byzantines">拜占庭</nuxt-link
              ><nuxt-link to="/units/Cataphract">聖騎兵</nuxt-link
              >時他們對弓箭手的防禦加成會讓熱那亞弩手略為感到頭痛。
            </li>
            <li>
              熱那亞弩手是一個全面的單位，它能對付大多數弓箭手害怕的<nuxt-link
                to="/units/Knight"
                >騎士</nuxt-link
              >以及<nuxt-link to="/units/Infantry_Units">步兵</nuxt-link
              >。有一定數量後也可對付一些較弱的弓兵單位，不過
              <nuxt-link to="/Rattan_units/Archer">藤甲弓手</nuxt-link
              >和<nuxt-link to="/Plumed_units/Archer">羽毛箭射手</nuxt-link
              >還是能贏過他們的。騎兵部隊仍然可以在一對一的戰鬥中擊敗熱那亞弩手。
              <nuxt-link to="/units/Mangonel">投石車</nuxt-link
              >對熱那亞弩手仍舊是個威脅，不過他們有足夠的HP可以扛一下傷害。<nuxt-link
                to="/units/Elite_Skirmisher"
                >戰矛兵</nuxt-link
              >、
              <nuxt-link to="/units/Genitour">標槍騎兵</nuxt-link>、<nuxt-link
                to="/units/Huskarl"
                >哥德衛隊</nuxt-link
              >以及<nuxt-link to="/units/Eagle_Warrior">鷹勇士</nuxt-link
              >都是熱那亞弩手需要特別注意的。他們可以與
              <nuxt-link to="/civs/Italians">義大利</nuxt-link>廉價的<nuxt-link
                to="/units/Hand_Cannoneer"
                >火槍兵</nuxt-link
              >配合讓敵人變成砲灰。
            </li>
            <li>
              熱那亞弩兵對各種艦船也有攻擊加成。事實上，兩名精銳熱那亞弩手就能擊沉一艘完全升級的<nuxt-link
                to="/units/Galleon"
                >重型弩炮戰船</nuxt-link
              >，而擊沉同一艘船則需要十名
              <nuxt-link to="/units/Arbalest">強弩兵</nuxt-link
              >，這使得熱那亞弩兵能夠很好地防禦沿海襲擊。
            </li>
            <li>
              與大多數單位相反，熱那亞弩手在升級時獲得更快的攻擊速率。開火速率從3.05秒/次
              提升到2.03秒/次，基本上使精銳熱那亞弩手的射速快兩倍。所以盡快升級精銳是玩家要考慮的事情，因為會大大增加他們的傷害輸出。
            </li>
          </ul>
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
            <td class="tta4">
              <nuxt-link to="/units/Cavalry_Units">騎兵單位</nuxt-link
              >、<nuxt-link to="/Cavalry_units/Archer">馬騎弓兵</nuxt-link>、
              <nuxt-link to="/units/Infantry_Units">步兵單位</nuxt-link>。
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:30%">劣勢(不易對抗)</td>
            <td class="tta4">
              <nuxt-link to="/units/Archer_Units">弓兵單位</nuxt-link
              >、<nuxt-link to="/units/Scorpion">弩炮</nuxt-link>、<nuxt-link
                to="/units/Mangonel"
                >投石車</nuxt-link
              >、
              <nuxt-link to="/units/Huskarl">哥德衛隊</nuxt-link>、<nuxt-link
                to="/units/Eagle_Warrior"
                >鷹勇士</nuxt-link
              >、<nuxt-link to="/units/Samurai">日本武士</nuxt-link>。
            </td>
          </tr>
          <tr class="tta">
            <td class="unit" colspan="2" style="text-align: center;">
              <div class="unititle">升級</div>
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">攻擊力</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Fletching.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Fletching">箭羽</nuxt-link>(+1)
              <br />
              <img
                class="gg"
                src="~assets/Bodkinarrow.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Bodkin_Arrow">錐狀箭頭</nuxt-link>(+1)
              <br />
              <img
                class="gg"
                src="~assets/Bracer.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Bracer">護腕</nuxt-link>(+1)
              <br />
              <img
                class="gg"
                src="~assets/Chemistry.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Chemistry">化學</nuxt-link>(+1)
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">攻擊範圍</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Fletching.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Fletching">箭羽</nuxt-link>(+1)
              <br />
              <img
                class="gg"
                src="~assets/Bodkinarrow.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Bodkin_Arrow">錐狀箭頭</nuxt-link>(+1)
              <br />
              <img
                class="gg"
                src="~assets/Bracer.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Bracer">護腕</nuxt-link>(+1)
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">開火速度</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Thumb_Ring.png"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Thumb_Ring">拇指環</nuxt-link>(+18%)
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">命中率</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Ballistics.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Ballistics">彈道學</nuxt-link
              >:對移動目標命中率上升
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">防禦</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Paddedarcherarmor.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Padded_Archer_Armor">弓兵布甲</nuxt-link
              >(+1/+1)
              <br />
              <img
                class="gg"
                src="~assets/Leatherarcherarmor.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Leather_Archer_Armor">弓兵皮甲</nuxt-link
              >(+1/+1)
              <br />
              <img
                class="gg"
                src="~assets/Ringarcherarmor.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Ring_Archer_Armor">弓兵環甲</nuxt-link
              >(+1/+2)
              <br />
              <img
                class="gg"
                src="~assets/CastleAgeUnique.png"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Pavise">巨盾</nuxt-link>(+1/+1，<nuxt-link
                to="/civs/Italians"
                >義大利</nuxt-link
              >限定)
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">招降抵抗</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Faith.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Faith">忠誠信仰</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">生產速度</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Conscription.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Conscription">徵兵制度</nuxt-link>(+33%)
            </td>
          </tr>
        </table>

        <h3>剋熱那亞弩手的單位</h3>
        <div class="hrn1"></div>
        <div class="n1">
          以下單位擁有對熱那亞弩手的額外傷害，按造傷殺力排列。
          <div class="n1">
            <div class="row">
              <div class="col-md-6">
                <div style="margin:12px 0px;"><strong>+15攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/CannonGalleonIcon.jpg"
                      alt=""
                    />
                    <nuxt-link to="/units/Cannon_Galleon">火砲戰船</nuxt-link>→
                    <img
                      class="gg"
                      src="~assets/CannonGalleonIcon.jpg"
                      alt=""
                    />
                    <nuxt-link to="/units/Elite_Cannon_Galleon"
                      >精銳火砲戰船</nuxt-link
                    >
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+12攻擊</strong></div>
                <ul>
                  <li>
                    <img class="gg" src="~assets/SMURI.jpg" alt="" /><nuxt-link
                      to="/units/Samurai"
                      >精銳日本武士</nuxt-link
                    >(<nuxt-link to="/civs/Japanese">日本</nuxt-link>限定)
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+10攻擊</strong></div>
                <ul>
                  <li>
                    <img class="gg" src="~assets/HuskarlIcon.jpg" alt="" />
                    <nuxt-link to="/units/Huskarl">精銳哥德衛隊</nuxt-link
                    >(<nuxt-link to="/civs/Goths">哥德</nuxt-link>限定)
                  </li>
                  <li>
                    <img class="gg" src="~assets/SMURI.jpg" alt="" /><nuxt-link
                      to="/units/Samurai"
                      >日本武士</nuxt-link
                    >(<nuxt-link to="/civs/Japanese">日本</nuxt-link>限定)
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+6攻擊</strong></div>
                <ul>
                  <li>
                    <img class="gg" src="~assets/HuskarlIcon.jpg" alt="" />
                    <nuxt-link to="/units/Huskarl">哥德衛隊</nuxt-link
                    >(<nuxt-link to="/civs/Goths">哥德</nuxt-link>限定)
                  </li>
                </ul>
              </div>
              <div class="col-md-6">
                <div style="margin:12px 0px;"><strong>+5攻擊</strong></div>
                <ul>
                  <li>
                    <img class="gg" src="~assets/GenitourIcon.jpg" alt="" />
                    <nuxt-link to="/units/Genitour">精銳標槍騎兵</nuxt-link
                    >(<nuxt-link to="/civs/Berbers">柏柏</nuxt-link>和同盟限定)
                  </li>
                  <li>
                    <img
                      class="gg"
                      src="~assets/Imperialskirmishericon.png"
                      alt=""
                    />
                    <nuxt-link to="/units/Imperial_Skirmisher"
                      >帝王戰矛兵</nuxt-link
                    >(<nuxt-link to="/civs/Vietnamese">越南</nuxt-link
                    >和同盟限定)
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+4攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/EliteSkirmisherIcon.jpg"
                      alt=""
                    />
                    <nuxt-link to="/units/Elite_Skirmisher">戰矛兵</nuxt-link>
                  </li>
                  <li>
                    <img class="gg" src="~assets/GenitourIcon.jpg" alt="" />
                    <nuxt-link to="/units/Genitour">標槍騎兵</nuxt-link
                    >(<nuxt-link to="/civs/Berbers">柏柏</nuxt-link>和同盟限定)
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+3攻擊</strong></div>
                <ul>
                  <li>
                    <img class="gg" src="~assets/SkirmisherIcon.jpg" alt="" />
                    <nuxt-link to="/units/Skirmisher">矛兵</nuxt-link>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          以下團隊加成可讓以下單位對熱那亞弩手有額外攻擊力
          <div class="n1">
            <nuxt-link to="/civs/Persians">波斯</nuxt-link
            >在團隊加成裡，給予以下單位+2額外攻擊vs<nuxt-link
              to="/units/Archer_Units"
              >射手單位</nuxt-link
            >。
            <div class="row">
              <div class="col-md-6">
                <div style="margin:12px 0px;"><strong>+2攻擊</strong></div>
                <ul>
                  <li>
                    <img class="gg" src="~assets/KnightIcon.jpg" alt="" />
                    <nuxt-link to="/units/Knight">騎士</nuxt-link>→
                    <img class="gg" src="~assets/CavalierIcon.jpg" alt="" />
                    <nuxt-link to="/units/Cavalier">騎兵</nuxt-link>→
                    <img class="gg" src="~assets/PaladinIcon.jpg" alt="" />
                    <nuxt-link to="/units/Paladin">遊俠</nuxt-link>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <h3>團隊加成</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              <nuxt-link to="/civs/Berbers">柏柏</nuxt-link>：<nuxt-link
                to="/techs/Kasbah"
                >聚居堡壘</nuxt-link
              >能夠提高熱那亞弩手的生產速度還有加速
              <nuxt-link to="/techs/Conscription">徵兵制度</nuxt-link
              >、<nuxt-link to="/techs/Pavise">巨盾</nuxt-link>的研究時間(快25%)
            </li>
            <li>
              <nuxt-link to="/civs/Magyars">馬札爾</nuxt-link
              >：熱那亞弩手視野+2。。
            </li>
            <li>
              <nuxt-link to="/civs/Malians">馬利</nuxt-link>：研究<nuxt-link
                to="/techs/Chemistry"
                >化學</nuxt-link
              >和<nuxt-link to="/techs/Ballistics">彈道學</nuxt-link>速度快80%。
            </li>
            <li>
              <nuxt-link to="/civs/Saracens">薩拉森</nuxt-link
              >：熱那亞弩手對<nuxt-link
                to="/armor/Armor_Class_Standard_Building"
                >標準建築</nuxt-link
              >攻擊+1。
            </li>
            <li>
              <nuxt-link to="/civs/Teutons">條頓</nuxt-link
              >：熱那亞弩手更不容易被招降。
            </li>
          </ul>
        </div>
        <h3>更新日誌</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <h3>
            <em><nuxt-link to="/games/aof">失落的帝國</nuxt-link></em>
          </h3>
          <ul>
            <li>熱那亞弩手訓練需50木50金。</li>
          </ul>
          <h3>
            <em><nuxt-link to="/games/ak">非洲王朝</nuxt-link></em>
          </h3>
          <ul>
            <li>
              熱那亞弩手對<nuxt-link to="/armor/Armor_Class_Camel"
                >駱駝單位</nuxt-link
              >攻擊+5。
            </li>
          </ul>
          <h3>
            <em><nuxt-link to="/games/aor">王者崛起</nuxt-link></em>
          </h3>
          <ul>
            <li>熱那亞弩手訓練需45木45金。</li>
            <li>
              5.7改版後熱那亞弩手現在對<nuxt-link to="/armor/Armor_Class_Camel"
                >駱駝單位</nuxt-link
              >攻擊+6。
            </li>
          </ul>
        </div>
        <h3>趣事</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <li>
            在<nuxt-link to="/games/aof">《世紀帝國:失落的帝國》</nuxt-link
            >的mod版本中，熱那亞弩手使用修改過的火槍兵模組。然而，在零售版中，他們獲得了新的模組:攜帶著盾牌的弩手。
          </li>
          <li>
            熱那亞弩手的盾牌外觀與巨盾很相似，巨盾是中世紀歐洲弓箭手使用的一種高凸形盾牌，作為一種移動掩護物，可以在沒有射擊的情況下躲在後面，儘管單位似乎永遠不會在蹲下時與敵人交戰，因此在面對遠程對手時這個盾牌有點沒用。同樣在現實中，這個巨盾比弓手高很多，而在遊戲中卻要短得多。但是，他們在移動時確實在背上攜帶了這種巨盾，這跟歷史是相符的。。
          </li>
          <li>
            熱那亞弩手是少數對馬弓騎兵有攻擊加成的弓兵單位，其他則有<nuxt-link
              to="/units/Elite_Skirmisher"
              >戰矛兵</nuxt-link
            >、
            <nuxt-link to="/units/Imperial_Skirmisher">帝王戰矛兵</nuxt-link
            >、<nuxt-link to="/units/Genitour">精銳標槍騎兵</nuxt-link
            >和<nuxt-link to="/Camel_units/Archer">駱駝弓騎兵</nuxt-link>。
          </li>
          <li>
            熱那亞弩手對騎兵的加成傷害可能是指教皇在1096年禁止武器的禁令。禁令的頒布是因為一名經過多年軍事訓練的騎士可輕易地被一個幾乎沒有受過訓練或使用過弩的農民殺死。結果，弩被認為是對統治精英的威脅，讓他們遊說羅馬天主教會禁止這些武器。
          </li>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td
              class="unit"
              colspan="2"
              style="background-color:#3c763d;text-align: center;"
            >
              <div class="unititle" style="color: #fff">熱那亞弩手</div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img
                  src="~assets/New_Genoese_Crossbowman.png"
                  width="45"
                  alt=""
                />
              </div>
            </td>
          </tr>
          <tr>
            <td
              class="unit"
              colspan="2"
              style="background-color:#3c763d;text-align: center;"
            >
              <div class="unititle2" style="color: #fff">單位介紹</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">類型</td>
            <td class="unit4">
              <nuxt-link to="/units/Archer_Units">弓兵</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">文明</td>
            <td class="unit4">
              <nuxt-link to="/civs/Italians">義大利</nuxt-link>
            </td>
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
                src="~assets/Castleicon.png"
                width="45"
                alt=""
              /><nuxt-link to="/building/Castle">城堡</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">訓練時間</td>
            <td class="unit4">22/19(精銳)秒</td>
          </tr>
          <tr>
            <td
              class="unit"
              colspan="2"
              style="background-color:#3c763d;text-align: center;"
            >
              <div class="unititle2" style="color: #fff">成本</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">木材</td>
            <td class="unit4">45</td>
          </tr>
          <tr>
            <td class="unit3">黃金代</td>
            <td class="unit4">45</td>
          </tr>
          <tr>
            <td
              class="unit"
              colspan="2"
              style="background-color:#3c763d;text-align: center;"
            >
              <div class="unititle2" style="color: #fff">數據</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">血量</td>
            <td class="unit4">45/50(精銳)</td>
          </tr>
          <tr>
            <td class="unit3">攻擊</td>
            <td class="unit4">6(遠程)</td>
          </tr>
          <tr>
            <td class="unit3">攻擊加成</td>
            <td class="unit4">
              對<nuxt-link to="/armor/Armor_Class_Cavalry">騎兵攻擊</nuxt-link
              >+5/+7(精銳) <br />對<nuxt-link
                to="/armor/Armor_Class_War_Elephant"
                >戰象</nuxt-link
              >+5/+7(精銳) <br />對<nuxt-link to="/armor/Armor_Class_Camel"
                >駱駝騎兵</nuxt-link
              >+4/+6(精銳) <br />對<nuxt-link to="/armor/Armor_Class_Ship"
                >船隻</nuxt-link
              >+4/+5(精銳)
            </td>
          </tr>
          <tr>
            <td class="unit3">攻擊速度</td>
            <td class="unit4">3.05/2.03(精銳)</td>
          </tr>
          <tr>
            <td class="unit3">開火間隔</td>
            <td class="unit4">5</td>
          </tr>
          <tr>
            <td class="unit3">射程</td>
            <td class="unit4">4</td>
          </tr>
          <tr>
            <td class="unit3">命中率</td>
            <td class="unit4">100%</td>
          </tr>
          <tr>
            <td class="unit3">發射速度</td>
            <td class="unit4">7</td>
          </tr>
          <tr>
            <td class="unit3">近防</td>
            <td class="unit4">1</td>
          </tr>
          <tr>
            <td class="unit3">遠防</td>
            <td class="unit4">0</td>
          </tr>
          <tr>
            <td class="unit3">防禦類別</td>
            <td class="unit4">
              <nuxt-link to="/armor/Armor_Class_Archer">弓兵</nuxt-link> <br />
              <nuxt-link to="/armor/Armor_Class_Unique_Unit"
                >特殊單位</nuxt-link
              >
            </td>
          </tr>
          <tr>
            <td class="unit3">跑速</td>
            <td class="unit4">0.96</td>
          </tr>
          <tr>
            <td class="unit3">視野</td>
            <td class="unit4">8</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2"><nuxt-link to="">單位演變</nuxt-link></div>
            </td>
          </tr>
          <tr>
            <td class="unit3">升級到</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/New_Genoese_Crossbowman.png"
                alt=""
              />精銳熱那亞弩手
            </td>
          </tr>
          <tr>
            <td class="unit3">升級成本</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/Elite-unique-research.jpg"
                alt=""
              />900食物750黃金
            </td>
          </tr>
          <tr>
            <td class="unit3">升級時間</td>
            <td class="unit4">60秒</td>
          </tr>
        </table>

        <div class="thanks">感謝! 此頁面由賜齡協助編輯</div>
      </div>
      <div class="col-md-12">
        <h3>圖庫</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <div class="col-md-12">
            <div class="col-md-4">
              <nuxt-link to="/img/Genoesecrossbowman.png"
                ><img
                  class="imgn hg"
                  src="~assets/Genoesecrossbowman.png"
                  alt=""
              /></nuxt-link>
              <p><em>一群熱那亞弩手。</em></p>
            </div>
            <div class="col-md-4">
              <nuxt-link to="/img/Genoese_Crossbowmen.png"
                ><img
                  class="imgn hg"
                  src="~assets/Genoese_Crossbowmen.png"
                  alt=""
              /></nuxt-link>
              <p>
                <em
                  >一群戰鬥中的熱那亞弩手，請注意他們移動時背上會背著巨盾。</em
                >
              </p>
            </div>
            <div class="col-md-4">
              <nuxt-link to="/img/Genoese.png"
                ><img class="imgn hg" src="~assets/Genoese.png" alt=""
              /></nuxt-link>
              <p><em>Mod版(左)和零售版(右)的熱那亞弩手。</em></p>
            </div>
          </div>
          <div class="col-md-12">
            <div class="col-md-4">
              <nuxt-link to="/img/Genoese_Crossbowman_real_life.jpg"
                ><img
                  class="imgn hg"
                  src="~assets/Genoese_Crossbowman_real_life.jpg"
                  alt=""
              /></nuxt-link>
              <p>
                <em
                  >真實世界的熱那亞弩手(左邊的是<nuxt-link to="/techs/Pavise"
                    >巨盾</nuxt-link
                  >)。</em
                >
              </p>
            </div>
            <div class="col-md-4">
              <nuxt-link to="/img/Genoese_&_Condottiero (1).jpg"
                ><img
                  class="imgn hg"
                  src="~assets/Genoese_&_Condottiero (1).jpg"
                  alt=""
              /></nuxt-link>
              <p><em>義大利的特殊單位:傭兵(左)和熱那亞弩手(右)。</em></p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'allunit',
  components: {}
}
</script>
<style></style>
