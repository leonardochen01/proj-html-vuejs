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

    <div class="perfect-bread-text-container">
      <h4>
        fresh & tasty bakery every day
      </h4>

      <h1>
        The Perfect Fresh Bread
      </h1>

      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt ducimus sint distinctio voluptatem quod. Modi voluptatem impedit inventore dolorem odit?
      </p>
    </div>

    <div class="explore">
      <a href="#">Explore our products</a>
    </div>


  </header>

</template>

<style>

.site-header{
  height: 100vh;
  background-image: url(../assets/images/hero-header-bakery.jpg);
  background-size: cover;
}

.site-header-container{
  display: flex;
  justify-content: space-between;
  height: 30vh;
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
  padding-top: 3rem;
  padding-right: 3rem;
  height: 10vh;
}

a{
  color: rgb(85, 50, 139);
  text-decoration: none;
}

.perfect-bread-text-container{
  width: 30vw;
  height: 30vh;
  margin-left: 150px;
}

h4{
  color: rgb(85, 50, 139);
  font-size: 1rem;
  text-transform: uppercase;
  font-weight: 100;
}

h1{
  color: rgb(85, 50, 139);
  font-size: 4rem;
}

p{
  font-size: 1.2rem;
  font-weight: 100;
}

.explore{
  width: 20vw;
  height: 5vh;
  margin-left: 200px;
  margin-top: 50px;
}

</style>