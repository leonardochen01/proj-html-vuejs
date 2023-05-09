<script>

export default {
  name: "Header",
};

</script>

<template>

  <header class="site-header">
    <div class="site-header-container">
      <div class="site-logo">
        <a href="/">
          <img src="../assets/images/avada-bakery-logo.png" alt="Logo"/>
        </a>
      </div>
      <nav class="site-nav">
        <ul>
          <li>
            <a href="#">Home</a>
          </li>
          <li>
            <a href="#">Shop</a>
          </li>
          <li>
            <a href="#">About</a>
          </li>
          <li>
            <a href="#">Gallery</a>
          </li>
          <li>
            <a href="#">Contact</a>
          </li>
          <li>
            <a href="#">Locations</a>
          </li>
          <li>
            <a href="#">Journal</a>
          </li>
          <li>
            <a href="#">Contact</a>
          </li>
          <li>
            <a href="#">My account</a>
          </li>
          <li>
            <a href="#">
              <i class="fa-solid fa-cart-shopping"></i>
            </a>
          </li>
        </ul>
      </nav>
    </div>
  </header>

</template>

<style scoped>

.site-header{
  height: 10vh;
}

.site-header-container{
  height: 100%;
  display: flex;
  justify-content: space-between;
}

.site-logo img{
  max-height: 100px;
  padding-left: 3rem;
}

.site-nav ul{
  font-size: 0.75rem;
  text-transform: uppercase;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  display: flex;
  list-style: none;
  gap: 3rem;
  align-items: center;
  height: 100%;
  padding-right: 3rem;
}

a{
  color: rgb(85, 50, 139);
  text-decoration: none;
}

</style>