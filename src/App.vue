<script>

</script>

<template>
  <div class="container">

    <!-- Banner azzurro -->
    <div class="banner">
      <p>Everything about Lifestyle, Travel and Gadgets!</p>
      <span>SIGN IN</span>
      <span>ABOUT US</span>
      <span>CONTACT US</span>
      <span>BUY NOW</span>
    </div>
    <!-- /Banner azzurro -->

    <!-- Logo -->
    <div class="header-logo">
      <img src="./assets/img/logo-default-slim.png" alt="">
    </div>
    <!-- /Logo -->

    <!-- Nav bar -->
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
    <!-- /Nav bar -->

    <!-- Jumbo -->
    <div class="row gap-4">
      <div class="col-4 a"></div>
      <div class="col-4 b"></div>
      <div class="col-4 c"></div>
      <div class="col-4 d"></div>
      <div class="col-4 e"></div>
      <div class="col-4 f"></div>
    </div>
    
    <!-- /Jumbo -->
  </div>
  
</template>

<style>
/* BANNER */
  .banner{
    background-color: #0088cc;
    color: white;
    display: flex;
    min-width: 1140px;
    align-items: center;
    height: 40px;
    font-weight: 300;
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
  }

  /* JUMBO */
  .row{
    justify-content: space-around;
  }
  .col-4{
    border: 1px solid;
    height: 200px;
    width: 400px;
    
  }
</style>
