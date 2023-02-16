<template>
  <!-- OffCanvas Cart Start -->
  <div id="offcanvas-cart" class="offcanvas offcanvas-cart">
    <div class="inner">
      <div class="head">
        <span class="title">Cart</span>
        <button class="offcanvas-close">×</button>
      </div>
      <div class="body customScroll">
        <ul class="minicart-product-list">
          <li>
            <a href="single-product.html" class="image"
              ><img
                src="assets/images/product-image/1.jpg"
                alt="Cart product Image"
            /></a>
            <div class="content">
              <a href="single-product.html" class="title"
                >Walnut Cutting Board</a
              >
              <span class="quantity-price"
                >1 x <span class="amount">$91.86</span></span
              >
              <a href="#" class="remove">×</a>
            </div>
          </li>
          <li>
            <a href="single-product.html" class="image"
              ><img
                src="assets/images/product-image/2.jpg"
                alt="Cart product Image"
            /></a>
            <div class="content">
              <a href="single-product.html" class="title"
                >Lucky Wooden Elephant</a
              >
              <span class="quantity-price"
                >1 x <span class="amount">$453.28</span></span
              >
              <a href="#" class="remove">×</a>
            </div>
          </li>
          <li>
            <a href="single-product.html" class="image"
              ><img
                src="assets/images/product-image/3.jpg"
                alt="Cart product Image"
            /></a>
            <div class="content">
              <a href="single-product.html" class="title">Fish Cut Out Set</a>
              <span class="quantity-price"
                >1 x <span class="amount">$87.34</span></span
              >
              <a href="#" class="remove">×</a>
            </div>
          </li>
        </ul>
      </div>
      <div class="foot">
        <div class="sub-total">
          <table class="table">
            <tbody>
              <tr>
                <td class="text-start">Sub-Total :</td>
                <td class="text-end">$523.30</td>
              </tr>
              <tr>
                <td class="text-start">Eco Tax (-2.00) :</td>
                <td class="text-end">$4.52</td>
              </tr>
              <tr>
                <td class="text-start">VAT (20%) :</td>
                <td class="text-end">$104.66</td>
              </tr>
              <tr>
                <td class="text-start">Total :</td>
                <td class="text-end theme-color">$632.48</td>
              </tr>
            </tbody>
          </table>
        </div>
        <div class="buttons">
          <a href="cart.html" class="btn btn-dark btn-hover-primary mb-30px"
            >view cart</a
          >
          <a href="checkout.html" class="btn btn-outline-dark current-btn"
            >checkout</a
          >
        </div>
        <p class="minicart-message">Free Shipping on All Orders Over $100!</p>
      </div>
    </div>
  </div>
  <!-- OffCanvas Cart End -->

  <!-- OffCanvas Menu Start -->
  <div id="offcanvas-mobile-menu" class="offcanvas offcanvas-mobile-menu">
    <button class="offcanvas-close"></button>
    <div class="inner customScroll">
      <div class="offcanvas-menu mb-20px">
        <ul>
          <li>
            <a href="#"><span class="menu-text">Home</span></a>
            <ul class="sub-menu">
              <li>
                <a href="index.html"><span class="menu-text">Home 1</span></a>
              </li>
              <li>
                <a href="index-2.html"><span class="menu-text">Home 2</span></a>
              </li>
            </ul>
          </li>
          <li><a href="about.html">About Us</a></li>
          <li>
            <a href="#"><span class="menu-text">Shop</span></a>
            <ul class="sub-menu">
              <li>
                <a href="#"><span class="menu-text">Shop Page</span></a>
                <ul class="sub-menu">
                  <li><a href="shop-3-column.html">Shop 3 Column</a></li>
                  <li><a href="shop-4-column.html">Shop 4 Column</a></li>
                  <li>
                    <a href="shop-left-sidebar.html">Shop Grid Left Sidebar</a>
                  </li>
                  <li>
                    <a href="shop-right-sidebar.html"
                      >Shop Grid Right Sidebar</a
                    >
                  </li>
                </ul>
              </li>
              <li>
                <a href="#"
                  ><span class="menu-text">product Details Page</span></a
                >
                <ul class="sub-menu">
                  <li><a href="single-product.html">Product Single</a></li>
                  <li>
                    <a href="single-product-variable.html">Product Variable</a>
                  </li>
                  <li>
                    <a href="single-product-affiliate.html"
                      >Product Affiliate</a
                    >
                  </li>
                  <li><a href="single-product-group.html">Product Group</a></li>
                  <li>
                    <a href="single-product-tabstyle-2.html">Product Tab 2</a>
                  </li>
                  <li>
                    <a href="single-product-tabstyle-3.html">Product Tab 3</a>
                  </li>
                </ul>
              </li>
              <li>
                <a href="#"
                  ><span class="menu-text">Single Product Page</span></a
                >
                <ul class="sub-menu">
                  <li>
                    <a href="single-product-slider.html">Product Slider</a>
                  </li>
                  <li>
                    <a href="single-product-gallery-left.html"
                      >Product Gallery Left</a
                    >
                  </li>
                  <li>
                    <a href="single-product-gallery-right.html"
                      >Product Gallery Right</a
                    >
                  </li>
                  <li>
                    <a href="single-product-sticky-left.html"
                      >Product Sticky Left</a
                    >
                  </li>
                  <li>
                    <a href="single-product-sticky-right.html"
                      >Product Sticky Right</a
                    >
                  </li>
                </ul>
              </li>
              <li>
                <a href="#"><span class="menu-text">Other Pages</span></a>
                <ul class="sub-menu">
                  <li><a href="cart.html">Cart Page</a></li>
                  <li><a href="checkout.html">Checkout Page</a></li>
                  <li><a href="compare.html">Compare Page</a></li>
                  <li><a href="wishlist.html">Wishlist Page</a></li>
                  <li><a href="my-account.html">Account Page</a></li>
                  <li><a href="login.html">Login & Register Page</a></li>
                  <li><a href="empty-cart.html">Empty Cart Page</a></li>
                </ul>
              </li>
            </ul>
          </li>
          <li>
            <a href="#"><span class="menu-text">Pages</span></a>
            <ul class="sub-menu">
              <li><a href="404.html">404 Page</a></li>
              <li><a href="privacy-policy.html">Privacy Policy</a></li>
              <li><a href="faq.html">Faq Page</a></li>
              <li><a href="coming-soon.html">Coming Soon Page</a></li>
            </ul>
          </li>
          <li>
            <a href="#"><span class="menu-text">Blog</span></a>
            <ul class="sub-menu">
              <li>
                <a href="#"><span class="menu-text">Blog Grid</span></a>
                <ul class="sub-menu">
                  <li>
                    <a href="blog-grid-left-sidebar.html"
                      >Blog Grid Left Sidebar</a
                    >
                  </li>
                  <li>
                    <a href="blog-grid-right-sidebar.html"
                      >Blog Grid Right Sidebar</a
                    >
                  </li>
                </ul>
              </li>
              <li>
                <a href="#"><span class="menu-text">Blog List</span></a>
                <ul class="sub-menu">
                  <li>
                    <a href="blog-list-left-sidebar.html"
                      >Blog List Left Sidebar</a
                    >
                  </li>
                  <li>
                    <a href="blog-list-right-sidebar.html"
                      >Blog List Right Sidebar</a
                    >
                  </li>
                </ul>
              </li>
              <li>
                <a href="#"><span class="menu-text">Blog Single</span></a>
                <ul class="sub-menu">
                  <li>
                    <a href="blog-single-left-sidebar.html"
                      >Blog Single Left Sidebar</a
                    >
                  </li>
                  <li>
                    <a href="blog-single-right-sidebar.html"
                      >Blog Single Right Sidbar</a
                    >
                  </li>
                </ul>
              </li>
            </ul>
          </li>
          <li><a href="contact.html">Contact Us</a></li>
        </ul>
      </div>
      <!-- OffCanvas Menu End -->

      <!-- Language Currency start -->
      <div class="offcanvas-userpanel mt-8">
        <ul>
          <!-- Language Start -->
          <li class="offcanvas-userpanel__role">
            <a href="#">English <i class="ion-ios-arrow-down"></i></a>
            <ul class="user-sub-menu">
              <li><a class="current" href="#">English</a></li>
              <li><a href="#"> Italiano</a></li>
              <li><a href="#"> Français</a></li>
              <li><a href="#"> Filipino</a></li>
            </ul>
          </li>
          <!-- Language End -->
          <!-- Currency Start -->
          <li class="offcanvas-userpanel__role">
            <a href="#">USD $ <i class="ion-ios-arrow-down"></i></a>
            <ul class="user-sub-menu">
              <li><a class="current" href="#">USD $</a></li>
              <li><a href="#">EUR €</a></li>
              <li><a href="#">POUND £</a></li>
              <li><a href="#">FRANC ₣</a></li>
            </ul>
          </li>
          <!-- Currency End -->
        </ul>
      </div>
      <!-- Language Currency End -->
      <div class="offcanvas-social mt-auto">
        <ul>
          <li>
            <a href="#"><i class="ion-social-facebook"></i></a>
          </li>
          <li>
            <a href="#"><i class="ion-social-twitter"></i></a>
          </li>
          <li>
            <a href="#"><i class="ion-social-google"></i></a>
          </li>
          <li>
            <a href="#"><i class="ion-social-youtube"></i></a>
          </li>
          <li>
            <a href="#"><i class="ion-social-instagram"></i></a>
          </li>
        </ul>
      </div>
    </div>
  </div>
  <!-- OffCanvas Menu End -->

  <div class="offcanvas-overlay"></div>
</template>
<script setup></script>

<style scoped></style>
