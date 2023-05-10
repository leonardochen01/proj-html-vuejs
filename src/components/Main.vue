<script>

export default{
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



  </main>

</template>

<style scoped>

@import url(../css/main1.css);
@import url(../css/main2.css);

</style>