<template>
  <div>
    <div>
      <Navbar />
    </div>
    <div class="jumbotron p-4 p-md-5 text-white rounded bg-dark">
      <div class="col-md-6 px-0">
        <h1 class="be-careful-to-respec">BE CAREFUL TO RESPECT THE DESIGN!</h1>
        <p class="technologies-html">
          Technologies : HTML CSS JS
          Détail des specs front : Zeplin
          3 maquettes desktop, tablet et mobile, 2 breakpoints
          Desktop/ tablet : 1200px (Desktop) / 1199 tablet
          Tablet / Mobile : 600px (Tablet) / 599 (mobile)
        </p>
        <button class="rectangle">Let's discover!</button>
      </div>
    </div>
    <div class="cart">
      <div class="row">
        <div class="col">
          <h1
            class="good-luck-about-this"
          >Good luck about this block. Don’t forget to respect the different breakpoints</h1>
        </div>
        <div class="col text-center">
          <p
            class="lorem-ipsum-dolor-si"
          >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
          <button class="rect">hang in there</button>
        </div>
      </div>
    </div>
    <div class="devid">
      <img src="../assets/img/trait.png" alt="devider" />
    </div>
    <div class="dont-forget-about-t">
      <h1>Don’t forget about the spacing! It’s very important</h1>
    </div>
    <div class="finalGroupe">
      <div class="row infinite">
        <div class="col text-center">
          <img src="../assets/img/icon-1.png" alt="icon-1" />
        </div>
        <div class="col text-center">
          <img src="../assets/img/icon-2.png" alt="icon-2" />
        </div>
        <div class="col text-center">
          <img src="../assets/img/icon-3.png" alt="icon-3" />
        </div>
      </div>
      <div class="row">
        <div class="col text-center">
          <h1 class="lorem-ipsum-title">Lorem ipsum</h1>
        </div>
        <div class="col text-center">
          <h1 class="lorem-ipsum-title">Lorem ipsum</h1>
        </div>
        <div class="col text-center">
          <h1 class="lorem-ipsum-title">Consulting</h1>
        </div>
      </div>
      <div class="row">
        <div class="col text-center">
          <p
            class="lorem-ipsum-text"
          >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
        </div>
        <div class="col text-center">
          <p
            class="lorem-ipsum-text"
          >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
        </div>
        <div class="col text-center">
          <p
            class="lorem-ipsum-text"
          >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
        </div>
      </div>
      <div class="row mt-5">
        <div class="col text-center">
          <button class="rect-final">It’s almost done, don’t give up</button>
        </div>
      </div>
    </div>
    <div class="footer">
      <div class="wrapper">
        <div class="row">
          <div class="col ml-5 text-center"></div>
          <div class="col ml-5 text-center">
            <h1 class="send-us-your-email-t text-light">Send us your email to stay tuned</h1>
          </div>
          <div class="col ml-5 text-center">
            <h1 class="send-us-your-email-t text-light">Follow us</h1>
          </div>
        </div>
        <div class="row">
          <div class="col ml-5 text-center">
            <p>
              <img src="../assets/img/logo-aleia.png" alt="logo-Aleia" />
            </p>
          </div>
          <div class="col ml-5 text-center">
            <div class="input-group">
              <input
                class="form-control"
                type="text"
                placeholder="yourmail@email.com"
                aria-label="Search"
              />
              <div class="input-group-append">
                <span class="input-group-text text-light" id="basic-text1">xoxo</span>
              </div>
            </div>
          </div>
          <div class="col ml-5 text-center">
            <p>
              <span>
                <img
                  src="../assets/img/facebook.png"
                  alt="logo-Aleia"
                  style=" width: 60px;height: 60px;"
                />
              </span>
              <span>
                <img
                  src="../assets/img/linkedin.png"
                  alt="logo-Aleia"
                  style=" width: 60px;height: 60px;"
                />
              </span>
              <span>
                <img
                  src="../assets/img/twitter.png"
                  alt="logo-Aleia"
                  style=" width: 60px;height: 60px;"
                />
              </span>
            </p>
          </div>
        </div>
        <div class="row mt-3">
          <div class="col text-center text-light">
            <small>© 2020. All rights reserved.</small>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "~/components/Navbar.vue";

export default {
  components: {
    Navbar
  }
};
</script>

<style scoped>
@font-face {
  font-family: "OpenSans-Regular";
  src: url("../assets/fonts/OpenSans-Regular.ttf");
  font-weight: normal;
  font-style: normal;
}
@font-face {
  font-family: "OpenSans-SemiBold";
  src: url("../assets/fonts/OpenSans-SemiBold.ttf");
  font-weight: normal;
  font-style: normal;
}
@font-face {
  font-family: "OpenSans-Bold";
  src: url("../assets/fonts/OpenSans-Bold.ttf");
  font-weight: normal;
  font-style: normal;
}
@font-face {
  font-family: "Montserrat-SemiBold";
  src: url("../assets/fonts/Montserrat-SemiBold.ttf");
  font-weight: normal;
  font-style: normal;
}

.jumbotron {
  background: url("../assets/img/fond-1.png") top no-repeat;
  height: 962px;
  background-color: #242726 !important;
  background-size: auto;
  background-position: 100% 100%;
}
.be-careful-to-respec {
  color: #ffffff;
  font-family: Montserrat;
  font-size: 58px;
  font-weight: 400;
  line-height: 70.7px;
  width: 637px;
  text-align: left;
  margin-top: 175px !important;
  margin-left: 144px !important;
  margin-right: 659px !important;
  font-family: "Montserrat-SemiBold";
}
.technologies-html {
  color: #bfbebf;
  font-size: 19px;
  font-weight: 400;
  line-height: 25.87px;
  width: 487px;
  text-align: justify;
  margin-top: 15px !important;
  margin-left: 144px !important;
  margin-right: 809px !important;
  font-family: "OpenSans-SemiBold";
}
.rectangle {
  border: 3px solid #2e8174;
  border-radius: 15px;
  width: 150px;
  height: 56px;
  background-color: #242726 !important;
  margin-top: 31px !important;
  margin-left: 267px !important;
  margin-right: 1023px !important;
  color: white;
  font-family: "OpenSans-SemiBold";
}
.rect {
  background-image: linear-gradient(
    47.99deg,
    #2e8174 0%,
    #30a996 42.53%,
    #00ffd9 100%
  );
  border-radius: 15px;
  width: 150px;
  height: 50px;
  margin-left: 168px !important;
  margin-bottom: 68px !important;
  margin-right: 299px !important;
  font-family: "OpenSans-SemiBold";
}
.rect-final {
  background-image: linear-gradient(
    47.99deg,
    #2e8174 0%,
    #30a996 42.53%,
    #00ffd9 100%
  );
  border-radius: 15px;
  width: 297px;
  height: 50px;
  margin-left: 168px !important;
  margin-bottom: 68px !important;
  margin-right: 299px !important;
  font-family: "OpenSans-SemiBold";
}
.cart {
  z-index: 1;
  background-color: #ffffff;
  box-shadow: 0 100px 100px 0 rgba(236, 236, 236, 0.5);
  margin-top: -86px !important;
  margin-left: 105px !important;
  margin-right: 95px !important;
  width: 1240px;
  height: 500px;
}
.good-luck-about-this {
  color: #000000;
  font-family: "Montserrat-SemiBold";
  font-size: 40px;
  font-weight: 400;
  line-height: 48.76px;
  text-align: justify;
  padding-top: 119px !important;
  padding-left: 148px !important;
  padding-bottom: 130px !important;
}
.lorem-ipsum-dolor-si {
  color: #807f7f;
  font-family: "OpenSans-SemiBold";
  font-size: 19px;
  font-weight: 400;
  line-height: 25.87px;
  text-align: justify;
  padding-top: 126px !important;
  padding-right: 114px !important;
  padding-bottom: 46px !important;
}
.devid {
  margin-top: 45px;
  margin-left: 105px !important;
}
.dont-forget-about-t {
  color: #000000;
  font-family: "Montserrat-SemiBold";
  font-size: 40px;
  font-weight: 400;
  line-height: 48.76px;
  width: 780px;
  text-align: justify;
  margin-top: 45px !important;
  margin-left: 327px !important;
  margin-right: 333px !important;
}
.finalGroupe {
  margin-top: 70px !important;
  margin-left: 144px !important;
  margin-right: 139px !important;
}
.lorem-ipsum-title {
  color: #000000;
  font-size: 25px;
  font-weight: 400;
  line-height: 30px;
  font-family: "Montserrat-SemiBold";
  margin-top: 6px !important;
}
.lorem-ipsum-text {
  color: #807f7f;
  font-family: "OpenSans-SemiBold";
  font-size: 19px;
  font-weight: 400;
  line-height: 25.87px;
  text-align: justify;
  margin-top: 24px !important;
}
.footer {
  padding-top: 50px;
  background-color: #242726;
  height: 270px;
}
.wrapper {
  margin-left: 86px !important;
  margin-right: 135px !important;
}
.send-us-your-email-t {
  font-family: "Montserrat-SemiBold";
  font-size: 19px;
  font-weight: 400;
  line-height: 23px;
  padding-bottom: 22px;
}
.input-group-text {
  background-color: #242726;
  color: #bcbaba;
}
.input-group {
  font-family: "Montserrat-SemiBold";
  font-size: 19px;
  font-weight: 400;
  line-height: 23px;
  text-align: justify;
}
</style>
