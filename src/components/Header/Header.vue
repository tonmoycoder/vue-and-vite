<template>
  <div class="header-top section-fluid bg-black">
    <div class="container">
      <div class="row row-cols-lg-2 align-items-center jus">
        <!-- Header Top Message Start -->
        <div class="col text-center text-lg-start">
          <div class="header-top-massege">
            <p>Default Welcome Message</p>
          </div>
        </div>
        <!-- Header Top Message End -->
        <!-- Header Top Language Currency -->
        <div class="col d-none d-lg-block">
          <div class="header-top-set-lan-curr d-flex justify-content-end">
            <!-- Single Wedge Start -->
            <div class="header-top-curr dropdown">
              <button class="dropdown-toggle" data-bs-toggle="dropdown">
                Language : (ENG) <i class="ion-ios-arrow-down"></i>
              </button>
              <ul class="dropdown-menu dropdown-menu-right">
                <li><a class="dropdown-item" href="#">English</a></li>
                <li><a class="dropdown-item" href="#">Italiano</a></li>
                <li><a class="dropdown-item" href="#">Français</a></li>
                <li><a class="dropdown-item" href="#">Filipino</a></li>
              </ul>
            </div>
            <!-- Single Wedge End -->
            <!-- Single Wedge Start -->
            <div class="header-top-curr dropdown">
              <button
                class="dropdown-toggle pr-0 border-0"
                data-bs-toggle="dropdown"
              >
                Currency : (USD) <i class="ion-ios-arrow-down"></i>
              </button>
              <ul class="dropdown-menu dropdown-menu-right">
                <li><a class="dropdown-item" href="#">USD $</a></li>
                <li><a class="dropdown-item" href="#">EUR €</a></li>
                <li><a class="dropdown-item" href="#">POUND £</a></li>
                <li><a class="dropdown-item" href="#">FRANC ₣</a></li>
              </ul>
            </div>
            <!-- Single Wedge End -->
          </div>
        </div>
        <!-- Header Top Language Currency -->
      </div>
    </div>
  </div>
  <!-- Header Top  End -->
</template>

<script setup></script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Raleway:wght@100;200;300;400;500;600;700;800;900&display=swap");
.header-top {
  padding: 16px 0;
}

.header-top-massege p {
  color: #ff7004;
  font-family: Raleway, sans-serif;
  font-weight: 600;
  font-style: italic;
  font-size: 14px;
}

.header-top-set-lan-curr {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  font-family: Raleway, sans-serif;
}

.header-top-set-lan-curr {
  flex-wrap: wrap;
  font-family: Raleway, sans-serif;
}

.header-top-set-lan-curr .dropdown .dropdown-toggle {
  font-size: 14px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  padding: 0 15px;
  -webkit-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  color: #fff;
  border: none;
  border-radius: 3px;
  background-color: transparent;
  border-right: 1px solid #43474e;
}

.header-top-set-lan-curr .dropdown .dropdown-toggle i {
  font-size: 18px;
  margin-left: 7px;
  color: #fff;
  -webkit-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  line-height: 23px;
}

.header-top-set-lan-curr .dropdown .dropdown-menu {
  margin: 0;
  top: 34px !important;
  left: auto !important;
  right: 0;
  min-width: 130px;
  overflow: hidden;
  padding: 0 15px;
  background: #fff;
  border-radius: 0;
  border: none;
  -webkit-box-shadow: 0 3px 25.5px 4.5px rgb(0 0 0 / 6%);
  box-shadow: 0 3px 25.5px 4.5px rgb(0 0 0 / 6%);
  -webkit-transform: translate3d(0, 0, 0) !important;
  transform: translate3d(0, 0, 0) !important;
  inset: 34px auto auto 0 !important;
}

.dropdown-menu {
  position: absolute;
  z-index: 1000;
  display: none;
  min-width: 10rem;
  padding: 0.5rem 0;
  margin: 0;
  font-size: 1rem;
  color: #212529;
  text-align: left;
  list-style: none;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 0.25rem;
}

ul {
  display: block;
  list-style-type: disc;
  margin-block-start: 1em;
  margin-block-end: 1em;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
  padding-inline-start: 40px;
}

.header-top-set-lan-curr {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  font-family: Raleway, sans-serif;
}
.header-top-set-lan-curr .dropdown .dropdown-menu li {
  border-bottom: 1px solid #ebebeb;
}
li {
  list-style: none;
}

.header-top-set-lan-curr .dropdown .dropdown-menu .dropdown-item {
  padding: 10px;
  color: #474747;
  line-height: 25px;
  font-size: 13px;
  background: 0 0;
}
.dropdown-item {
  display: block;
  width: 100%;
  padding: 0.25rem 1rem;
  clear: both;
  font-weight: 400;
  color: #212529;
  text-align: inherit;
  text-decoration: none;
  white-space: nowrap;
  background-color: transparent;
  border: 0;
}

body {
  font-family: "Open Sans", sans-serif;
  font-size: 16px;
  font-weight: 400;
  font-style: normal;
  line-height: 1.625;
  position: relative;
  visibility: visible;
  color: #474747;
}
</style>
