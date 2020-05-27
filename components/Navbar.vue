<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-white">
    <a class="logo-aleia" href="#">
      <img class="logo-aleia-image" src="../assets/img/logo-aleia.png" alt="logo-aleia" />
    </a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav text-dark">
        <li class="nav-item about-us">
          <a class="nav-link" href="#">About us</a>
        </li>
        <li class="nav-item services">
          <a class="nav-link" href="#">Services</a>
        </li>
        <li class="nav-item careers">
          <a class="nav-link" href="#">Careers</a>
        </li>
        <li class="nav-item functions">
          <a class="nav-link" href="#">Functions</a>
        </li>
        <li class="nav-item contact-us">
          <a class="nav-link" href="#">Contact us</a>
        </li>
        <li class="nav-item fr">
          <a class="nav-link" href="#">FR</a>
        </li>
      </ul>
    </div>
  </nav>
</template>
<style >
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
.logo-aleia {
  margin-bottom: 7px !important;
  margin-left: 50px !important;
  margin-top: 5px !important;
}
.navbar {
  padding-top: 0 !important;
  padding-bottom: 0 !important;
  height: 75px !important;
  width: 1440px !important;
}
.nav-item {
  padding-top: 50% !important;
  padding-bottom: 50% !important;
}
.about-us {
  font-size: 16px;
  font-weight: 400;
  line-height: 21.79px;
  text-align: left;
  font-family: "OpenSans-SemiBold";
  margin-left: 220px !important;
}
.services {
  font-size: 16px;
  font-weight: 400;
  line-height: 21.79px;
  text-align: left;
  font-family: "OpenSans-SemiBold";
  margin-left: 80px !important;
}
.careers {
  font-size: 16px;
  font-weight: 400;
  line-height: 21.79px;
  text-align: left;
  font-family: "OpenSans-SemiBold";
  margin-left: 80px !important;
}
.functions {
  font-size: 16px;
  font-weight: 400;
  line-height: 21.79px;
  text-align: left;
  font-family: "OpenSans-SemiBold";
  margin-left: 80px !important;
}
.contact-us {
  font-size: 16px;
  font-weight: 400;
  line-height: 21.79px;
  text-align: left;
  font-family: "OpenSans-SemiBold";
  margin-left: 128px !important;
}
.fr {
  font-size: 16px;
  font-weight: 400;
  line-height: 21.79px;
  text-align: left;
  font-family: "OpenSans-Regular";
  margin-left: 117px !important;
}
</style>
