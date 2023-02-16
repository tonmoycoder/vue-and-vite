<template>
  <!-- Header Top Message Start -->
  <div class="header-top section-fluid bg-black">
    <div class="container">
      <div class="row row-cols-lg-2 align-items-center">
        <!-- Header Top Message Start -->
        <div class="col text-center text-lg-start">
          <div class="header-top-massege">
            <p>{{ message }}</p>
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
  <!-- Header Top  End -->
</template>

<script setup>
const message = "This Is Default message";
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Raleway:wght@100;200;300;400;500;600;700;800;900&display=swap");
</style>
