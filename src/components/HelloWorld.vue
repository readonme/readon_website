<template>
  <div class="hello">
    <div class="header">
      <span class="title">ReadON</span>
      <span class="overview">overview</span>
    </div>
    <div class="sec sec1 sec-left">
      <div class="content">
        <p class="t2 font-point" style="color: rgba(255, 52, 0, 1)">ReadON</p>
        <p class="t2">Addicted to Reading</p>

        <p class="t3">
          ReadON is an amazing "Read to Earn" program that combines SOCIAL-FI
          AND GAME-FI.Get back into the habit of reading and get addicted, just
          like playing a game.
        </p>
        <el-row class="mb-4" style="margin-top: 3em">
          <el-button
            round
            class="buttom"
            style="color: white; background: #5961ec"
          >
            <a
              href="https://discord.gg/NCZG4nvrYT"
              target="_blank"
              style="color: white"
              >Join Discord</a
            >
          </el-button>

          <el-button round
            ><a
              href="https://whitepaper.readon.me"
              target="_blank"
              style="color: black"
              >White Paper</a
            ></el-button
          >
        </el-row>
      </div>
    </div>

    <div class="sec1-1">
      <iframe
        width="100%"
        height="100%"
        src="https://www.youtube.com/embed/b944n_sXrGk"
        title="ReadON Introduction"
        frameborder="10"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
    </div>

    <div class="sec sec2 sec-right">
      <div class="content">
        <p class="t2">
          Mint Your
          <span class="font-point" style="color: rgba(255, 52, 0, 1)">
            Nucleus
          </span>
        </p>
        <p class="t2">To Earn $READ</p>
        <p class="t3">
          Choose a nucleus you love as a NFT and start reading the game.Read,
          upgrade, and get achievements to earn extra tokens.
        </p>
      </div>
    </div>

    <div class="sec sec3 sec-left">
      <div class="content">
        <p class="t2">Unleashing Your Power</p>
        <p class="t2">
          Of
          <span class="font-point" style="color: rgba(255, 179, 0, 1)">
            Fission
          </span>
        </p>
        <p class="t3">
          Spread the content you like and let your friends feel your
          influence.Find people with the same hobbies and unlock your favorite
          props together to gain whitelist rights.
        </p>
      </div>
    </div>

    <div class="sec sec4 sec-right">
      <div class="content">
        <p class="t2">Feel the White Heat of</p>
        <p class="t2 font-point" style="color: rgba(0, 177, 255, 1)">Web3</p>
        <p class="t3">
          Wow, ReadON is a web3 project, it will take you into web3, don't miss
          it.Start by following our community and you will be involved in the
          governance of an exciting program!
        </p>
      </div>
    </div>
    <div class="sec5">
      <div class="content">
        <p class="t2" style="color: rgba(9, 238, 255, 1)">Team</p>
        <p class="t3">Meet some of the partners working on ReadON.</p>
        <el-row :gutter="15">
          <el-col :span="6" :xs="12">
            <div class="teambox">
              <img class="headimg" src="../assets/imgs/h1.png" />
              <p class="name" style="color: #50ccb4">Troy</p>
              <p class="role" style="background: #50ccb4">Co-Founder</p>
              <p class="">
                Graduated from Carnegie Mellon University with a degree in
                Computer Science. As a CTO with successful experience of NFT
                project.
              </p>
            </div>
          </el-col>
          <el-col :span="6" :xs="12">
            <div class="teambox">
              <img class="headimg" src="../assets/imgs/h2.png" />
              <p class="name" style="color: #ff7f42">Neo</p>
              <p class="role" style="background: #ff7f42">Co-Founder</p>
              <p class="">
                10 years of experience in internet media. The last project
                successfully landed in Indonesia, Thailand, and Saudi Arabia.
                Product Director of the Media-Game product that had 10 million
                DAUs.
              </p>
            </div>
          </el-col>

          <el-col :span="6" :xs="12">
            <div class="teambox">
              <img class="headimg" src="../assets/imgs/h3.png" />
              <p class="name" style="color: #b4ff67">Daniel Olano</p>
              <p class="role" style="background: #b4ff67">Ambassador</p>
              <p class="">
                Polkadot Senior Ambassador. 5 years + Web3 experience, founder
                of virto.network project.
              </p>
            </div>
          </el-col>

          <el-col :span="6" :xs="12">
            <div class="teambox">
              <img class="headimg" src="../assets/imgs/h4.png" />
              <p class="name" style="color: #8fc764">Kevin Diego</p>
              <p class="role" style="background: #8fc764">Tech Partner</p>
              <p class="">
                Head of development for a 30 million DAU product from 0 to 1.
                Experience in the development of multiple Play to Earn products
                with more than one million DAU.
              </p>
            </div>
          </el-col>

          <el-col :span="6" :xs="12">
            <div class="teambox">
              <img class="headimg" src="../assets/imgs/h5.png" />
              <p class="name" style="color: #737c7e">Fairy</p>
              <p class="role" style="background: #737c7e">Product Partner</p>
              <p class="">
                Former IBM data intelligence engineer. 5 years experience in
                content and ad distribution algorithms for millions DAU APP.
              </p>
            </div>
          </el-col>

          <el-col :span="6" :xs="12">
            <div class="teambox">
              <img class="headimg" src="../assets/imgs/h6.png" />
              <p class="name" style="color: #88a2fe">Yuki Kato</p>
              <p class="role" style="background: #88a2fe">UI Designer</p>
              <p class="">
                Her impressive artwork of user avatar drawing will be
                distributed to ReadON users by airdrop.
              </p>
            </div>
          </el-col>

          <el-col :span="6" :xs="12">
            <div class="teambox">
              <img class="headimg" src="../assets/imgs/h7.png" />
              <p class="name" style="color: #02b6b9">Danielle</p>
              <p class="role" style="background: #02b6b9">Front End Engineer</p>
              <p class="">
                Former front end engineer of bytedance with 8 years experience.
              </p>
            </div>
          </el-col>
        </el-row>
      </div>
    </div>

    <div class="footer">
      <div class="foot-main">
        <p>Make you addicted to Reading like a Game.</p>

        <div class="box">
          <a href="https://twitter.com/ReadOnMe3" target="_blank">
            <img class="b-title" src="../assets/imgs/twitter.png"/></a>
          <a href="https://discord.gg/NCZG4nvrYT" target="_blank">
            <img class="b-title" src="../assets/imgs/discord.png"/></a>
          <img class="b-title" src="../assets/imgs/telegram.png" />
          <a href="https://readonofficial.medium.com/" target="_blank"
            ><img class="b-title" src="../assets/imgs/medium.png"/></a>
        </div>

        <div class="line_02"></div>
        <p>Copyright 2022. All Right Reserved</p>
      </div>
      <img class="foot-shadow" src="../assets/imgs/shadow.png" />
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>
 
<style scoped>
a {
  text-decoration: none;
}
/* header*/
.header {
  background-color: black;
  color: white;
  height: 3.5em;
  line-height: 3.5em;
  border-bottom: 1px solid white;
}
.title {
  text-align: left;
  padding-left: 10%;
  font-weight: bold;
  font-size: 2.5em;
}
.overview {
  float: right;
  text-align: right;
  padding-right: 10%;
  font-size: 1.5em;
}

/*section*/
.buttom {
  border: none;
  font-weight: bold;
}
.font-point {
  font-weight: bolder;
  font-size: 1.1em;
  white-space: nowrap;
}

.t2 {
  font-weight: bold;
  font-size: 3.5em;
  color: white;
  margin-top: 0.5em;
}
.t3 {
  font-style: normal;
  font-weight: lighter;
  font-size: 1.5em;
  color: rgba(245, 245, 245, 1);
  letter-spacing: 1px;
  margin-top: 0.5em;
}
.sec {
  padding-top: 7em;
  padding-bottom: 7em;
  background: #000;
}
.sec1 {
  background: #000 url(../assets/imgs/s1.png) no-repeat center top;
  background-size: 70%;
}
.sec2 {
  background: #000 url(../assets/imgs/s2.png) no-repeat center top;
  background-size: 60%;
}
.sec3 {
  background: #000 url(../assets/imgs/s3.png) no-repeat center top;
  background-size: 70%;
}
.sec4 {
  background: #000 url(../assets/imgs/s4.png) no-repeat center top;
  background-size: 70%;
}

.sec1-1 {
  margin: 0 auto;
  width: 50em;
  height: 30em;
}

.contect {
  margin: 0 auto;
}

.sec-left {
  text-align: left;
  padding-left: 10%;
  padding-right: 48%;
}

.sec-right {
  text-align: right;
  padding-left: 48%;
  padding-right: 10%;
}

.sec5 {
  margin-top: 2em;
  padding: 0 10%;
}
.sec5 p {
  color: white;
}
.teambox {
  border: 2px solid white;
  border-radius: 1.5em;
  padding: 1.5em;
  height: 25em;
  margin: 1em auto;
  font-size: 0.8em;
}

.name {
  text-align: center;
  color: white;
  font-size: 1.5em;
  font-weight: 900;
}
.role {
  color: white;
  width: 70%;
  text-align: center;
  margin: 1em auto;
  font-size: 1.2em;
  font-weight: 900;
  padding: 0.5em;
  border-radius: 2em;
}
.headimg {
  width: 50%;
  margin-left: 25%;
}

/*footer */
.footer {
  margin: 0 auto;
  width: 80%;
  padding: 5em;
}
.foot-main > p {
  margin: 0 auto;
  text-align: center;
  width: 75%;
  font-size: 1.2em;
  padding: 1em;
}

.foot-main {
  background-color: white;
  border: 1px solid;
  border-radius: 20px;
}
.foot-shadow {
  width: 100%;
  margin-top: -8px;
}
.foot-shadow1 {
  margin-top: 0em;
  border-top: 50px solid #5a5756;
  border-left: 50px solid transparent;
  border-right: 50px solid transparent;
  background-image: linear-gradient(#e66465, #9198e5);
}

.box {
  display: flex;
  margin: 1em auto;
  width: 40%;
}

.b-title {
  height: 2em;
  display: flex;
  align-items: center;
  justify-content: left;
  margin-right: 3em;
}

.line_02 {
  width: 70%;
  margin: 0 auto;
  height: 1px;
  border-top: 1px solid black;
  text-align: center;
}

@media screen and (max-width: 900px) {
  .sec {
    background-size: cover;
  }
  .teambox {
    padding: 0.5em;
  }
  .sec1-1 {
    width: 80%;
    height: 20em;
  }
}
@media screen and (max-width: 600px) {
  .t2 {
    font-size: 2em;
  }
  .t3 {
    font-size: 1em;
  }
  .sec-left {
    text-align: left;
    padding: 3em 1em;
  }
  .sec-right {
    text-align: right;
    padding: 3em 1em;
  }
  .footer {
    margin: 0 auto;
    width: 95%;
    padding: 0;
  }
  .box {
    display: flex;
    width: 55%;
  }
  .b-title {
    height: 1em;
    display: flex;
    align-items: center;
    justify-content: left;
    margin-right: 1em;
  }
  .b-title :nth-last-child(3) {
    margin-right: 0;
  }
  .title {
    padding-left: 5%;
  }
  .role {
    font-size: 1em;
    width: 80%;
  }
  .sec5 {
    padding: 0 5%;
  }
  .sec1-1 {
    width: 80%;
    height: 12em;
  }
}

@media screen and (min-width: 401px) and (max-width: 850px) {
  .box {
    display: flex;
    width: 66%;
  }
}
</style>
