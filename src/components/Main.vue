<script>
export default {
  name: "Main",
};
</script>

<template>

  <main class="site-main">

    <div class="cookie-container d-flex align-items-center justify-content-between">

      <div class="cookie-text">
        <h6>
          our products
        </h6>
        <h1>
          All our delectable pastries are backed fresh in our Kitchen very morning, and are made with all-natural, all organic ingredients
        </h1>
        <button>Start Shopping</button>
      </div>

      <div class="cookie-image-container d-flex">
        <div class="cookie-image-1">
          <img src="../assets/images/choco-chip-cookies-1200x1530.jpg" alt="">
        </div>

        <div class="cookie-image-2">
          <img src="../assets/images//strawberry-jam-cookies-1200x1530.jpg" alt="">
        </div>
      </div>

    </div> <!--cookie container end-->

    <div class="moments-container">

      <div class="moments-title-container">
        <h6>
          corporate & weddings
        </h6>
        <h1>
          Baking Special Moments
        </h1>
      </div>

      <div class="moments-image-container d-flex justify-content-evenly">
        <div class="moments-image-1">
          <img src="../assets/images/corporate-bg.jpg" alt="">
        </div>
        <div class="moments-image-1">
          <img src="../assets/images/wedding-bg.jpg" alt="">
        </div>
      </div>

    </div> <!--moments container end-->

    <div class="product-container d-flex justify-content-between align-items-center">
      <div class="product-text d-flex flex-column gap-3 px-4 align-items-center justify-content-center">
        <h1>
          Find a freshly baked product perfect for you
        </h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste ipsam cumque doloremque, perspiciatis error aut nemo harum sapiente voluptas fugiat!
        </p>
        <button>Shop All Products</button>
      </div>

      <div class="product-image-container d-flex">   <!--CAROUSEL-->
        <img src="../assets/images/choco-chip-cookies-1200x1530.jpg" alt="">
        <img src="../assets/images/strawberry-jam-cookies-1200x1530.jpg" alt="">
        <img src="../assets/images/strawberry-donut-1200x1530.jpg" alt="">
        <img src="../assets/images/perfect-macarons-1200x1530.jpg" alt="">
      </div>

    </div> <!--product container end-->

    <div class="tell-us-container">

      <div class="d-flex justify-content-between">
        <h1>
          Tell us what you have in mind
        </h1>
        <h2>
          01
        </h2>
      </div>

      <div class="tell-us-text">
        <h3>
          manual ingredient selection
        </h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum numquam fugit accusamus eum mollitia suscipit nisi incidunt ad! Aut, nihil sit quibusdam ad doloremque dolores esse provident porro perspiciatis unde excepturi veniam fuga repudiandae iusto vel, tempora alias laboriosam voluptatibus.
        </p>
      </div>

    </div> <!--tell us container end-->

    <div class="we-start-container d-flex">

      <div class="we-start-image">

        <div class="d-flex mb-5">
          <h1>
            We Start Baking
          </h1>
  
          <h2>
            02
          </h2>
        </div>

        <div class="we-start-image-text">
          <h3>
            sweet & delicious
          </h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. At, vero suscipit. Mollitia animi optio eos delectus pariatur dicta, consectetur, totam, doloribus tempore assumenda soluta provident rem debitis culpa repellendus velit?
          </p>
        </div>


      </div>

      <div class="we-start-text">

        <div class="d-flex flex-column justify-content-between">
          <h3 style="color:black">
            dont just take our word for it
          </h3>
          <h5>
            "Finally found an alternative to the mass produced products.Something that incorporates real organic ingredients, nutrient dense wellness while promoting sustainability and activity"
          </h5>
          <h6>
            Rachel Cooper, Founder
          </h6>
        </div>

      </div>

    </div> <!--we start container end-->

    <div class="delivered-container">

      <div class="delivered-title d-flex justify-content-between">
        <h1>Delivered to your home</h1>
        <h2>03</h2>
      </div>

      <div class="delivered-text">
        <h3>baked to order & gift wrapped</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis dolore et culpa! Laudantium perspiciatis, libero sit quaerat molestias mollitia inventore dignissimos ipsum velit numquam consectetur expedita minus dolorem vel error.</p>
      </div>

    </div> <!--delivered container end-->

  </main>

</template>

<style scoped>

@import url(../css/main1.css);
@import url(../css/main2.css);
@import url(../css/main3.css);
@import url(../css/main4.css);

</style>