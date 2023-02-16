<template>
  <div class="header section">
    <Header />
    <HeaderTwo />
    <MainHeader />
  </div>
  <OffCanvas />
  <section>
    <Slider />
  </section>
  <section>
    <Category />
  </section>
  <section>
    <Product />
  </section>
  <section>
    <Banner />
  </section>
  <section>
    <Blog />
  </section>
  <section>
    <Social />
  </section>
  <Footer>
    <Footer />
  </Footer>
  <Modal />
</template>
<script setup>
import Header from "./components/Header/Header.vue";
import HeaderTwo from "./components/Header/Header-bottom.vue";
import MainHeader from "./components/Header/MainMenu.vue";
import OffCanvas from "./components/Offcanvas/OffCanvas.vue";
import Category from "./components/Category/Category.vue";
import Slider from "./components/Slider/Slider.vue";
import Product from "./components/Products/Products.vue";
import Banner from "./components/Banner/Banner.vue";
import Blog from "./components/Blog/Blog.vue";
import Social from "./components/Social/Social.vue";
import Footer from "./components/Footer/Footer.vue";
import Modal from "./components/Modal/Modal.vue";
</script>

<style scoped></style>
