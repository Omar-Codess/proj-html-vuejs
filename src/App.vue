<script>

</script>

<template>
  <!-- Banner azzurro -->
  <div class="banner">
    <div class="container banner-container">
      <p>Everything about Lifestyle, Travel and Gadgets!</p>
      <span>SIGN IN</span>
      <span>ABOUT US</span>
      <span>CONTACT US</span>
      <span>BUY NOW</span>
    </div>
  </div>
  <!-- /Banner azzurro -->

  <!-- Logo -->
  <div class="header-logo">
    <div class="container">
      <img src="./assets/img/logo-default-slim.png" alt="">
    </div>
  </div>
  <!-- /Logo -->
  
  <!-- Nav bar -->
  <div class="container">
    <div class="nav-bar">
      <div class="left-side">
        <span>HOME</span>
        <span>ELEMENTS</span>
        <span>FEATURES</span>
        <span>PAGES</span>
        <span>PORTFOLIO</span>
        <span>BLOG</span>
        <span>SHOP</span>
      </div>
      <div class="right-side">
        <i class="fa-solid fa-magnifying-glass"></i>
      </div>
    </div>
  </div>
  <!-- /Nav bar -->

  <!-- Jumbo -->
  <div class="jumbo">
    <div class="container">
      <div class="row gap-4">
        <div class="col-4 a">
          <div class="col-text">
            <p>PHOTOGRAPHY</p>
            <h5>How To Take Better Concert Pictures in 30 Seconds</h5>
          </div>
        </div>
        <div class="col-4 b">
          <div class="col-text">
            <p>GADGETS</p>
            <h5>Gadgets That Make Your Smartphone Even Smarter</h5>
          </div>
        </div>
        <div class="col-4 c">
          <div class="col-text">
            <p>TRAVEL</p>
            <h5>20 Top-Rated Tourist Attractions in Manhattan</h5>
          </div>
        </div>
        <div class="col-4 d">
          <div class="col-text">
            <p>LIFESTYLE</p>
            <h5>The Best Way to Ride a Motorcycle</h5>
          </div>
        </div>
        <div class="col-4 e">
          <div class="col-text">
            <p>TRAVEL</p>
            <h5>5 Fun Things to Do at the Beach</h5>
          </div>
        </div>
        <div class="col-4 f"><div class="col-text">
            <p>RECIPES</p>
            <h5>Amazingly Fresh Fruit And Herb Drinks For Summer</h5>
          </div></div>
      </div>
    </div>
  </div>
  <!-- /Jumbo -->
  

</template>

<style>
/* BANNER */
  .banner-container{
    color: white;
    display: flex;
    min-width: 1140px;
    align-items: center;
    height: 40px;
    font-weight: 300;
  }

  .banner{
    background-color: #0088cc;
  }

  .banner p{
    margin-right: 2em;
    margin-top: 1em;
  }

  .banner span{
    margin-right: 1em;
  }

  /* LOGO */
  .header-logo{
    border-bottom: solid 1px #f7f7f7;

  }

  .header-logo img{
    margin-top: 1em;
    max-width: 120px;
    margin-bottom: 1em;
  }

  /* NAV BAR */
  .nav-bar{
    display: flex;
    justify-content: space-between;
    font-weight: 600;
    margin-top: .8em;
    margin-bottom: .8em;
  }

  .left-side span{
    margin-right: 1em;
    font-weight: 700;
  }

  /* JUMBO */
  .jumbo{
    background-color: #d6d6d6;
  }

  .row{
    justify-content: space-around;
    padding-top: 2em;
    padding-bottom: 2em;
  }

  .col-4{
    height: 200px;
    width: 400px;
    color: white;
    font-weight: 600;
    display: flex;
    align-items: flex-end;
  }
    /* Cards */
    .a {
      background-image: url(./assets/img/blog-46.jpg);
      background-position: center;
      background-size: cover;
      background-repeat: no-repeat;
    }

    .b {
      background-image: url(./assets/img/blog-47.jpg);
      background-position: center;
      background-size: cover;
      background-repeat: no-repeat;
    }

    .c {
      background-image: url(./assets/img/blog-48.jpg);
      background-position: center;
      background-size: cover;
      background-repeat: no-repeat;
    }

    .d {
      background-image: url(./assets/img/blog-49.jpg);
      background-position: center;
      background-size: cover;
      background-repeat: no-repeat;
    }

    .e {
      background-image: url(./assets/img/blog-50.jpg);
      background-position: center;
      background-size: cover;
      background-repeat: no-repeat;
    }

    .f {
      background-image: url(./assets/img/blog-51.jpg);
      background-position: center;
      background-size: cover;
      background-repeat: no-repeat;
    }
    
    .col-text h5{
      font-weight: 700;
    }

    .col-text p{
      background-color: #0088cc;
      width: 35%;
      text-align: center;
      padding: .3em;
    }
    
</style>
