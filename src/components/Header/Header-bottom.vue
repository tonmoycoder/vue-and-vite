<template>
  <!-- Header Bottom  Start -->
  <div class="header-bottom d-none d-lg-block">
    <div class="container position-relative">
      <div class="row align-self-center">
        <!-- Header Logo Start -->
        <div class="col-auto align-self-center">
          <div class="header-logo">
            <a href="Header.vue"
              ><img src="../../assets/images/logo/logo.png" alt="Site Logo"
            /></a>
          </div>
        </div>
        <!-- Header Logo End -->

        <!-- Header Action Start -->
        <div class="col align-self-center">
          <div class="header-actions">
            <div class="header_account_list">
              <a href="javascript:void(0)" class="header-action-btn search-btn"
                ><i class="icon-magnifier"></i
              ></a>
              <div class="dropdown_search">
                <form class="action-form" action="#">
                  <input
                    class="form-control"
                    placeholder="Enter your search key"
                    type="text"
                  />
                  <button class="submit" type="submit">
                    <i class="icon-magnifier"></i>
                  </button>
                </form>
              </div>
            </div>
            <!-- Single Wedge Start -->
            <div class="header-bottom-set dropdown">
              <button
                class="dropdown-toggle header-action-btn"
                data-bs-toggle="dropdown"
              >
                <i class="icon-user"></i>
              </button>
              <ul class="dropdown-menu dropdown-menu-right">
                <li>
                  <a class="dropdown-item" href="my-account.html">My account</a>
                </li>
                <li>
                  <a class="dropdown-item" href="checkout.html">Checkout</a>
                </li>
                <li><a class="dropdown-item" href="login.html">Sign in</a></li>
              </ul>
            </div>
            <!-- Single Wedge End -->
            <a
              href="#offcanvas-cart"
              class="header-action-btn header-action-btn-cart offcanvas-toggle pr-0"
            >
              <i class="icon-handbag"></i>
              <span class="header-action-num">01</span>
              <!-- <span class="cart-amount">€30.00</span> -->
            </a>
            <a
              href="#offcanvas-mobile-menu"
              class="header-action-btn header-action-btn-menu offcanvas-toggle d-lg-none"
            >
              <i class="icon-menu"></i>
            </a>
          </div>
        </div>
        <!-- Header Action End -->
      </div>
    </div>
  </div>
  <!-- Header Bottom  End -->
</template>

<script setup></script>

<style scoped>
.header-bottom-set {
  margin: 0 14px;
}
.header-bottom {
  padding: 14px;
}
.header-actions {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: end;
  -ms-flex-pack: end;
  justify-content: flex-end;
}
.header_account_list {
  position: relative;
}

.header-actions .header-action-btn {
  position: relative;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  text-decoration: none;
  color: #000;
}

.header-actions .header-action-btn {
  position: relative;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  text-decoration: none;
  color: #000;
}
.header-actions .header-action-btn i {
  font-size: 24px;
  line-height: 1;
}
.header_account_list .dropdown_search {
  min-width: 600px;
  display: none;
  position: absolute;
  right: 0;
  top: 40px;
  z-index: 2;
}
.header_account_list .dropdown_search .action-form {
  position: relative;
}
.action-form {
  position: relative;
}
.form-control {
  display: block;
  width: 100%;
  min-height: 45px;
  padding: 6px 80px 6px 20px;
  font-size: 14px;
  font-weight: 400;
  line-height: 1.625;
  color: #474747;
  border-radius: 5px;
  background-color: #fff;
}
.header_account_list .dropdown_search .submit {
  position: absolute;
  top: 0;
  left: auto;
  right: 0;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  width: 60px;
  height: 100%;
  background: #ff7004;
  color: #fff;
  font-size: 20px;
  border-radius: 0 5px 5px 0;
  -webkit-box-shadow: none;
  box-shadow: none;
  outline: 0;
}
[type="button"]:not(:disabled),
[type="reset"]:not(:disabled),
[type="submit"]:not(:disabled),
button:not(:disabled) {
  cursor: pointer;
}
.header_account_list .dropdown_search .submit {
  position: absolute;
  top: 0;
  left: auto;
  right: 0;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  width: 60px;
  height: 100%;
  background: #ff7004;
  color: #fff;
  font-size: 20px;
  border-radius: 0 5px 5px 0;
  -webkit-box-shadow: none;
  box-shadow: none;
  outline: 0;
}
.header_account_list .dropdown_search .action-form {
  position: relative;
}
.header_account_list .dropdown_search {
  min-width: 600px;
  display: none;
  position: absolute;
  right: 0;
  top: 40px;
  z-index: 2;
}
.header_account_list {
  position: relative;
}
</style>
