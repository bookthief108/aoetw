<template>
  <!-- Main jumbotron for a primary marketing message or call to action
    -->
  <div class="container">
    <!-- Example row of columns -->
    <div class="row padtop">
      <div class="col-md-12">
        <h1>民兵</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            民兵是步兵單位，可以在<nuxt-link to="/building/Barracks"
              >軍營</nuxt-link
            >被訓練。
          </p>
        </div>
        <h3>戰術</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <p>
            民兵，在亞洲華人圈俗稱棒棒，是<nuxt-link to="/techs/age/Dark_Age"
              >黑暗時代</nuxt-link
            >唯一能生產的軍事單位，早年大家覺得民兵沒什麼用處，但隨著時代的變遷，今天的民兵已經變成一種主流打法，控制得宜可以有效的騷擾對方經濟，取得非常大的優勢。以步兵為主的文明，如
            <nuxt-link to="/civs/Celts">賽爾特</nuxt-link>、
            <nuxt-link to="/civs/Goths">哥德</nuxt-link>、
            <nuxt-link to="/civs/Japanese">日本</nuxt-link>和
            <nuxt-link to="/civs/Aztecs">阿茲特克</nuxt-link
            >都是非常凶殘的民兵快攻文明。
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
            <td class="tta4">
              <nuxt-link to="/units/Skirmisher">矛兵</nuxt-link>、<nuxt-link
                to="/units/Scout_Cavalry"
                >斥侯</nuxt-link
              >、 <nuxt-link to="/units/Spearman">槍兵</nuxt-link>、<nuxt-link
                to="/units/Villager"
                >村民</nuxt-link
              >。
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:30%">劣勢(不易對抗)</td>
            <td class="tta4">幾乎所有單位。</td>
          </tr>
          <tr class="tta">
            <td class="" colspan="2" style="text-align: center;">
              <div class="unititle">升級</div>
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">攻擊力</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Forging.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Forging">鍛造</nuxt-link>(+1)
              <br />
              <img
                class="gg"
                src="~assets/Ironcasting.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Iron_Casting">鑄造</nuxt-link>(+1)
              <br />
              <img
                class="gg"
                src="~assets/Blastfurnace.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Blast_Furnace">鼓風爐</nuxt-link>(+2)
              <br />
              <img
                class="gg"
                src="~assets/Arson.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Arson">縱火</nuxt-link
              >:步兵+2攻擊vs<nuxt-link to="/armor/Armor_Class_standard_building"
                >標準建築</nuxt-link
              >
              <br />
              <img
                class="gg"
                src="~assets/Unique-tech.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Garland_Wars">榮冠戰爭</nuxt-link
              >:步兵攻擊+4，<nuxt-link to="/civs/Aztecs">阿茲特克</nuxt-link
              >限定。
              <br />
              <img
                class="gg"
                src="~assets/Unique-tech.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Druzhina">王家侍從</nuxt-link
              >:步兵單位有踐踏傷害，<nuxt-link to="/civs/Slavs"
                >斯拉夫</nuxt-link
              >限定。
              <br />
              <img
                class="gg"
                src="~assets/CastleAgeUnique.png"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Chieftains">酋長</nuxt-link
              >:步兵對騎兵攻擊+5，對駱駝騎兵攻擊+4，<nuxt-link
                to="/civs/Vikings"
                >維京</nuxt-link
              >限定。
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">防禦</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Scalemailarmor.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Scale_Mail_Armor">步兵鱗甲</nuxt-link
              >(+1/+1)
              <br />
              <img
                class="gg"
                src="~assets/Chainmailarmor.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Chain_Mail_Armor">步兵鎖甲</nuxt-link
              >(+1/+1)
              <br />
              <img
                class="gg"
                src="~assets/Platemailarmor.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Plate_Mail_Armor">步兵板甲</nuxt-link
              >(+1/+2)
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">速度</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Squires.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Squires">護衛</nuxt-link>(+10%)
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">視野</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Tracking.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Tracking">追縱技術</nuxt-link>(+2)
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
              <br />
              <img
                class="gg"
                src="~assets/Heresy.png"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Heresy">異端邪說</nuxt-link>
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
              <br />
              <img
                class="gg"
                src="~assets/Unique-tech.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Perfusion">灌注士氣</nuxt-link
              >:兵營工作速率加快2倍，<nuxt-link to="/civs/Goths">哥德</nuxt-link
              >限定。
            </td>
          </tr>
          <tr>
            <td class="tta1" style="width:10%">生產成本</td>
            <td class="tta4">
              <img
                class="gg"
                src="~assets/Unique-tech.jpg"
                width="30"
                alt=""
              /><nuxt-link to="/techs/Forced_Levy">強制徵兵</nuxt-link
              >:軍營步兵單位訓練不需花黃金，<nuxt-link to="/civs/Malay"
                >馬來</nuxt-link
              >限定。
            </td>
          </tr>
        </table>

        <h3>剋裝甲步兵的單位與建築</h3>
        <div class="hrn1"></div>
        <div class="n1">
          以下單位擁有對裝甲步兵的額外傷害，按造傷殺力排列。
          <div class="n1">
            <div class="col-md-12">
              <div class="col-md-6">
                <div style="margin:12px 0px;"><strong>+15攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/CannonGalleonIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Cannon_Galleon">火砲戰船</nuxt-link
                    >→
                    <img
                      class="gg"
                      src="~assets/CannonGalleonIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Elite_Cannon_Galleon"
                      >精銳火砲戰船</nuxt-link
                    >
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+12攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/CataphractIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Cataphract">精銳聖騎兵</nuxt-link
                    >(<nuxt-link to="/civs/Byzantines">拜占庭</nuxt-link>限定)
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+11攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/JaguarWarriorIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Jaguar_Warrior"
                      >精銳豹勇士</nuxt-link
                    >(<nuxt-link to="/civs/Aztecs">阿茲特克</nuxt-link>限定)
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+10攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/HandCannoneerIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Hand_Cannoneer">火槍兵</nuxt-link>
                  </li>
                  <li>
                    <img
                      class="gg"
                      src="~assets/Slingericon.png"
                      alt=""
                    /><nuxt-link to="/units/Slinger">投石手</nuxt-link
                    >(<nuxt-link to="/civs/Incas">印加</nuxt-link>限定)
                  </li>
                  <li>
                    <img
                      class="gg"
                      src="~assets/JaguarWarriorIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Jaguar_Warrior">豹勇士</nuxt-link
                    >(<nuxt-link to="/civs/Aztecs">阿茲特克</nuxt-link>限定)
                  </li>
                </ul>
              </div>
              <div class="col-md-6">
                <div style="margin:12px 0px;"><strong>+9攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/CataphractIcon.jpg"
                      alt=""
                    /><nuxt-link to="/units/Cataphract">聖騎兵</nuxt-link
                    >(<nuxt-link to="/civs/Byzantines">拜占庭</nuxt-link>限定)
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+2攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/PlumedArcherIcon.jpg"
                      alt=""
                    /><nuxt-link to="/Plumed_units/Archer"
                      >精銳羽毛箭射手</nuxt-link
                    >(<nuxt-link to="/civs/Mayans">馬雅</nuxt-link>限定)
                  </li>
                </ul>
                <div style="margin:12px 0px;"><strong>+1攻擊</strong></div>
                <ul>
                  <li>
                    <img
                      class="gg"
                      src="~assets/PlumedArcherIcon.jpg"
                      alt=""
                    /><nuxt-link to="/Plumed_units/Archer">羽毛箭射手</nuxt-link
                    >(<nuxt-link to="/civs/Mayans">馬雅</nuxt-link>限定)
                  </li>
                </ul>
              </div>
            </div>
          </div>
          技術:以下技術會給以下單位對裝甲步兵有額外攻擊。
          <div class="n1">
            <img class="gg" src="~assets/Unique-tech.jpg" width="22" alt="" />
            <nuxt-link to="/techs/Parthian_Tactics">後勤學</nuxt-link>
            <div style="margin:12px 0px;"><strong>+6攻擊</strong></div>
            <ul>
              <li>
                <img
                  class="gg"
                  src="~assets/CataphractIcon.jpg"
                  alt=""
                /><nuxt-link to="/units/Cataphract"> 聖騎兵</nuxt-link>→
                <img
                  class="gg"
                  src="~assets/CataphractIcon.jpg"
                  alt=""
                /><nuxt-link to="/units/Cataphract">精銳聖騎兵</nuxt-link
                >(<nuxt-link to="/civs/Byzantines">拜占庭</nuxt-link>限定)
              </li>
            </ul>
          </div>
        </div>
        <h3>文明加成</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>
              <nuxt-link to="/civs/Aztecs">阿茲特克</nuxt-link
              >：民兵生產速度提高15％。
            </li>
            <li>
              <nuxt-link to="/civs/Burmese">緬甸</nuxt-link
              >：民兵在封建/城堡/帝王時代有 +1/+2/+3攻擊。
            </li>
            <li>
              <nuxt-link to="/civs/Celts">賽爾特</nuxt-link>：民兵移動加快15％。
            </li>
            <li>
              <nuxt-link to="/civs/Chinese">中國</nuxt-link
              >：利於民兵的技術在封建/城堡/帝王時代便宜10％/15％/20％。
            </li>
            <li>
              <nuxt-link to="/civs/Goths">哥德</nuxt-link
              >：民兵從封建時代開始便宜35％並對<nuxt-link
                to="/armor/Armor_Class_Building"
                >建築物</nuxt-link
              >攻擊+1。研發
              <nuxt-link to="/techs/Perfusion">灌注士氣</nuxt-link
              >後研發<nuxt-link to="/techs/Tracking">追縱技術</nuxt-link
              >、<nuxt-link to="/techs/Squires">護衛</nuxt-link>、
              <nuxt-link to="/techs/Arson">縱火</nuxt-link
              >和升級裝甲步兵的速度快100%。
            </li>
            <li>
              <nuxt-link to="/civs/Japanese">日本</nuxt-link
              >：民兵攻速快33％(從封建時代開始)。
            </li>
            <li>
              <nuxt-link to="/civs/Magyars">馬札爾</nuxt-link
              >：免費升級<nuxt-link to="/techs/Forging">鍛造</nuxt-link
              >、<nuxt-link to="/techs/Iron_Casting">鑄造</nuxt-link>和
              <nuxt-link to="/techs/Blast_Furnace">鼓風爐</nuxt-link>。
            </li>
            <li>
              <nuxt-link to="/civs/Malians">馬利</nuxt-link
              >：民兵在封建/城堡/帝王時代有 +1/+2/+3 遠程護甲。
            </li>
            <li>
              <nuxt-link to="/civs/Portuguese">葡萄牙</nuxt-link
              >：民兵黃金成本減少15％。
            </li>
            <li>
              <nuxt-link to="/civs/Slavs">斯拉夫</nuxt-link>：免費<nuxt-link
                to="/techs/Tracking"
                >追縱技術</nuxt-link
              >。
            </li>
            <li>
              <nuxt-link to="/civs/Spanish">西班牙</nuxt-link>：<nuxt-link
                to="/building/Blacksmith"
                >兵工廠</nuxt-link
              >對長槍兵有利的科技升級不須黃金。
            </li>
            <li>
              <nuxt-link to="/civs/Vietnamese">越南</nuxt-link>：免費<nuxt-link
                to="/techs/Conscription"
                >徵兵制度</nuxt-link
              >。
            </li>
            <li>
              <nuxt-link to="/civs/Vikings">維京</nuxt-link
              >：民兵在封建/城堡/帝王時代加10％/15％/20％的生命值。
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
              >能夠加速<nuxt-link to="/techs/Conscription">徵兵制度</nuxt-link
              >、的研究時間(快25%)。
            </li>
            <li>
              <nuxt-link to="/civs/Goths">哥德</nuxt-link
              >：民兵訓練和升級快20%。研發<nuxt-link to="/techs/Tracking"
                >追縱技術</nuxt-link
              >、 <nuxt-link to="/techs/Squires">護衛</nuxt-link>、<nuxt-link
                to="/techs/Arson"
                >縱火</nuxt-link
              >科技的時間快20%。
            </li>
            <li>
              <nuxt-link to="/civs/Teutons">條頓</nuxt-link
              >：民兵更不容易被招降。
            </li>
          </ul>
        </div>
        <h3>更新日誌</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <h3>
            <em><nuxt-link to="/games/aok">帝王世紀</nuxt-link></em>
          </h3>
          <ul>
            <li>民兵遠防是0。</li>
            <li>
              <nuxt-link to="/civs/Goths">哥德</nuxt-link
              >:在封建/城堡/帝王時代，民兵成本便宜10%/15%/25%。
            </li>
          </ul>
          <h3>
            <em><nuxt-link to="/games/aoc">征服者入侵</nuxt-link></em>
          </h3>
          <ul>
            <li>民兵現在擁有1的遠防。</li>
            <li>引入<nuxt-link to="/techs/Heresy">異端邪說</nuxt-link>。</li>
            <li>
              <nuxt-link to="/civs/Goths">哥德</nuxt-link
              >:1.0c後，哥德民兵從封建時代開始便宜35%。
            </li>
          </ul>
          <h3>
            <em><nuxt-link to="/games/ak">非洲王國</nuxt-link></em>
          </h3>
          <ul>
            <li>新科技<nuxt-link to="/techs/Arson">縱火</nuxt-link>引進。</li>
            <li>
              <nuxt-link to="/civs/Vikings">維京</nuxt-link
              >:4.8版本引進<nuxt-link to="/techs/Chieftains">酋長</nuxt-link
              >科技，民兵對
              <nuxt-link to="/armor/Armor_Class_Cavalry">騎兵單位</nuxt-link
              >有+5攻擊。
            </li>
            <li>
              <nuxt-link to="/civs/Vikings">維京</nuxt-link
              >:在4.8b版本後，<nuxt-link to="/techs/Chieftains">酋長</nuxt-link
              >讓民兵對駱駝有額外+2攻擊。
            </li>
          </ul>
          <h3>
            <em><nuxt-link to="/games/aor">王者崛起</nuxt-link></em>
          </h3>
          <ul>
            <li>
              <nuxt-link to="/civs/Vikings">維京</nuxt-link>:5.7版本<nuxt-link
                to="/techs/Chieftains"
                >酋長</nuxt-link
              >科技現在讓民兵對駱駝有額外+4攻擊。
            </li>
          </ul>
        </div>
        <h3>趣事</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <ul>
            <li>民兵是遊戲內唯一，三階以上升級的單位。</li>
            <li>民兵是黑暗時代唯一的軍事單位。</li>
            <li>
              馬來的民兵再研發<nuxt-link to="/techs/Forced_Levy"
                >強制徵兵</nuxt-link
              >後不用黃金。
            </li>
            <li>
              民兵是遊戲中少數四個沒有任何攻擊加成的單位。（另外三個是遊俠、貴族鐵騎與龜甲船）。
            </li>
          </ul>
        </div>
        <h3>圖庫</h3>
        <div class="hrn1"></div>
        <div class="n1">
          <div class="col-md-12">
            <div class="col-md-4">
              <nuxt-link to="/img/Militialine.png"
                ><img
                  class="imgn hg"
                  width="250"
                  src="~assets/Militialine.png"
                  alt=""
              /></nuxt-link>
              <p><em>民兵升級列表</em></p>
            </div>
            <div class="col-md-4">
              <nuxt-link to="/img/Militia.png"
                ><img
                  class="imgn hg"
                  width="250"
                  src="~assets/Militia.png"
                  alt=""
              /></nuxt-link>
              <p><em>一群民兵</em></p>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2">民兵</div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              <div class="unititle">
                <img src="~assets/MilitiaIcon.jpg" width="45" alt="" />
              </div>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2">單位介紹</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">類型</td>
            <td class="unit4">
              <nuxt-link to="/units/Infantry_Units">步兵</nuxt-link>
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
                src="~assets/Dark-age-logo-small.jpg"
                alt=""
              /><nuxt-link to="/techs/age/Dark_Age">黑暗時代</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">訓練於</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/Barracks-logo.jpg"
                alt=""
              /><nuxt-link to="/building/Barracks">軍營</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">訓練時間</td>
            <td class="unit4">21秒</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2">成本</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">肉</td>
            <td class="unit4">60</td>
          </tr>
          <tr>
            <td class="unit3">金</td>
            <td class="unit4">20</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2">數據</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">血量</td>
            <td class="unit4">40</td>
          </tr>
          <tr>
            <td class="unit3">攻擊</td>
            <td class="unit4">4(近戰)</td>
          </tr>
          <tr>
            <td class="unit3">攻擊速度</td>
            <td class="unit4">2.03</td>
          </tr>
          <tr>
            <td class="unit3">近防</td>
            <td class="unit4">0</td>
          </tr>
          <tr>
            <td class="unit3">遠防</td>
            <td class="unit4">1</td>
          </tr>
          <tr>
            <td class="unit3">防禦類型</td>
            <td class="unit4">
              <nuxt-link to="/armor/Armor_Class_Infantry">步兵</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">跑速</td>
            <td class="unit4">0.9</td>
          </tr>
          <tr>
            <td class="unit3">視野</td>
            <td class="unit4">4</td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#3c763d;;">
              <div class="unititle2">單位演變</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">升級到</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/ManAtArmsIcon.jpg"
                alt=""
              /><nuxt-link to="/units/Man-at-Arms">裝甲步兵</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">升級成本</td>
            <td class="unit4">
              <img
                class="gg"
                src="~assets/Man-at-arms-research.jpg"
                alt=""
              />100肉45金
            </td>
          </tr>
          <tr>
            <td class="unit3">升級時間</td>
            <td class="unit4">40</td>
          </tr>
        </table>

        <div class="thanks">感謝! 此頁面由眠協助編輯</div>
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
