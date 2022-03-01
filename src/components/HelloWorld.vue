<template>
  <div class="hello">
    <div class="header">
      <span class="title">ReadON</span>
      <span class="overview">overview</span>
    </div>
    <div class="sec sec1">
      <div class="content">
        <p class="t2 font-point"
           style="color: rgba(255, 52, 0, 1);">ReadON</p>
        <p class="t2">Addicted to Reading</p>
        <p class="t3">ReadON is an amazing "Read to Earn" program that combines SOCIAL-FI AND GAME-FI.Get back into the habit of reading and get addicted, just like playing a game.</p>
        <el-row class="mb-4"
                style="margin-top: 3em;">
          <el-button round
                     class="buttom"
                     style="color:white;background: #5961ec;">
            <a href="https://discord.gg/NCZG4nvrYT"
               target="_blank"
               style="color: white;">Join Discord</a>
          </el-button>

          <el-button round><a href="https://whitepaper.readon.me"
               target="_blank"
               style="color: black;">White Paper</a></el-button>

        </el-row>
      </div>
    </div>

    <div class="sec sec2">
      <div class="content">
        <p class="t2">Mint Your <span class="font-point"
                style="color: rgba(255, 52, 0, 1);"> Nucleus </span></p>
        <p class="t2">To Earn $READ</p>
        <p class="t3">Choose a nucleus you love as a NFT and start reading the game.Read, upgrade, and get achievements to earn extra tokens.
        </p>
      </div>
    </div>

    <div class="sec sec3">
      <div class="content">
        <p class="t2">Unleashing Your Power </p>
        <p class="t2">Of <span class="font-point"
                style="color:rgba(255,179,0,1);"> Fission </span></p>
        <p class="t3">Spread the content you like and let your friends feel your influence.Find people with the same hobbies and
          unlock your favorite props together to gain whitelist rights.
        </p>

      </div>
    </div>

    <div class="sec sec4">
      <div class="content">
        <p class="t2">Feel the White Heat of </p>
        <p class="t2 font-point"
           style="color:rgba(0,177,255,1);">Web3</p>
        <p class="t3">Wow, ReadON is a web3 project, it will take you into web3, don't miss it.Start by following our community and you will be involved in the governance of an exciting program!
        </p>

      </div>
    </div>

    <div class="footer">
      <div class="foot-main">
        <p> Make you addicted to Reading like a Game.</p>
        <div class="box">
          <a href="https://twitter.com/ReadOnMe3"
             target="_blank"> <img class="b-title"
                 src="../assets/imgs/twitter.png"></a>
          <a href="https://discord.gg/NCZG4nvrYT"
             target="_blank"> <img class="b-title"
                 src="../assets/imgs/discord.png"></a>
          <img class="b-title"
               src="../assets/imgs/telegram.png">
          <img class="b-title"
               src="../assets/imgs/medium.png">
        </div>

        <div class="line_02"></div>
        <p>Copyright 2022. All Right Reserved</p>
      </div>
      <img class="foot-shadow"
           src="../assets/imgs/shadow.png">
    </div>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  text-decoration: none;
}
/* header*/
.header {
  background-color: black;
  color: white;
  height: 2.5em;
  line-height: 2.5em;
  border-bottom: 1px solid white;
}
.title {
  text-align: left;
  padding-left: 10%;
  font-weight: bold;
  font-size: 1.5em;
}
.overview {
  float: right;
  text-align: right;
  padding-right: 10%;
  font-size: 1em;
  font-weight: bold;
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
  background: grey;
  background-repeat: no-repeat;
  background-size: 100% 100%;
  -moz-background-size: 100% 100%;
}
.sec1 {
  background-image: url(../assets/imgs/s1.png);
}
.sec2 {
  background-image: url(../assets/imgs/s2.png);
}
.sec3 {
  background-image: url(../assets/imgs/s3.png);
}
.sec4 {
  background-image: url(../assets/imgs/s4.png);
}

.contect {
  margin: 0 auto;
}

.sec:nth-child(even) {
  text-align: left;
  padding-left: 10%;
  padding-right: 48%;
}

.sec:nth-child(odd) {
  text-align: right;
  padding-left: 48%;
  padding-right: 10%;
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

@media screen and (max-width: 600px) {
  .t2 {
    font-size: 2em;
  }
  .t3 {
    font-size: 1em;
  }

  .sec:nth-child(even) {
    text-align: left;
    padding: 3em 1em;
  }
  .sec:nth-child(odd) {
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
}

@media screen and (min-width: 401px) and (max-width: 850px) {
  .box {
    display: flex;
    width: 66%;
  }
}
</style>
