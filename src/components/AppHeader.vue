<script>
export default {
    name: "AppHeader",
    data(){
      return {
      menu: [
        "HOME",
        "ELEMENTS",
        "FEATURES",
        "PAGES",
        "PORTFOLIO",
        "BLOG",
        "SHOP"
      ]
    }
  }
}
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
      <img src="../assets/img/logo-default-slim.png" alt="">
    </div>
  </div>
  <!-- /Logo -->
  
  <!-- Nav bar -->
  <div class="container">
    <div class="nav-bar">
      <div class="left-side">
        <span v-for="element in menu">{{ element }}</span>
        <!-- <span>ELEMENTS</span>
        <span>FEATURES</span>
        <span>PAGES</span>
        <span>PORTFOLIO</span>
        <span>BLOG</span>
        <span>SHOP</span> -->
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
        <div class="col-4 a hover">
          <div class="col-text">
            <p>PHOTOGRAPHY</p>
            <h5>How To Take Better Concert Pictures in 30 Seconds</h5>
          </div>
        </div>
        <div class="col-4 b hover">
          <div class="col-text">
            <p>GADGETS</p>
            <h5>Gadgets That Make Your Smartphone Even Smarter</h5>
          </div>
        </div>
        <div class="col-4 c hover">
          <div class="col-text">
            <p>TRAVEL</p>
            <h5>20 Top-Rated Tourist Attractions in Manhattan</h5>
          </div>
        </div>
        <div class="col-4 d hover">
          <div class="col-text">
            <p>LIFESTYLE</p>
            <h5>The Best Way to Ride a Motorcycle</h5>
          </div>
        </div>
        <div class="col-4 e hover">
          <div class="col-text">
            <p>TRAVEL</p>
            <h5>5 Fun Things to Do at the Beach</h5>
          </div>
        </div>
        <div class="col-4 f hover"><div class="col-text">
            <p>RECIPES</p>
            <h5>Amazingly Fresh Fruit And Herb Drinks For Summer</h5>
          </div></div>
      </div>
    </div>
  </div>
  <!-- /Jumbo -->
  
  <!-- Header footer -->
  <div class="container">
    <div class="row header-footer">
      <div class="col-4">
        <h6>POPULAR POSTS</h6>
        <div class="d-flex border-bottom pb-4 mt-2">
          <div class="img">
            <img src="../assets/img/blog-55.jpg" alt="">
          </div>
          <div class="text">
            <h6>Simple Ways to Have a Pretty Face</h6>
            <span>January 12, 2019</span>
          </div>
        </div>

        <div class="d-flex border-bottom pb-4 mt-2">
          <div class="img">
            <img src="../assets/img/blog-56.jpg" alt="">
          </div>
          <div class="text">
            <h6>Ranking the greatest players in basketball</h6>
            <span>January 12, 2019</span>
          </div>
        </div>

        <div class="d-flex border-bottom pb-4 mt-2">
          <div class="img">
            <img src="../assets/img/blog-57.jpg" alt="">
          </div>
          <div class="text">
            <h6>4 Ways to Look Cool in Glasses</h6>
            <span>January 12, 2019</span>
          </div>
        </div>

        <div class="d-flex border-bottom pb-4 mt-2">
          <div class="img">
            <img src="../assets/img/blog-58.jpg" alt="">
          </div>
          <div class="text">
            <h6>Top Camper Trailer Towing Tips</h6>
            <span>January 12, 2019</span>
          </div>
        </div>

        <div class="d-flex border-bottom pb-4 mt-2">
          <div class="img">
            <img src="../assets/img/blog-59.jpg" alt="">
          </div>
          <div class="text">
            <h6>5 Lovely Walks in New York</h6>
            <span>January 12, 2019</span>
          </div>
        </div>
      </div>

      <div class="col-4">
        <h6>RECENT POSTS</h6>
        <div class="d-flex border-bottom pb-4 mt-2">
          <div class="img">
            <img src="../assets/img/blog-65.jpg" alt="">
          </div>
          <div class="text">
            <h6>Main Reasons To Stop Texting And Driving</h6>
            <span>January 12, 2019</span>
          </div>
        </div>

        <div class="d-flex border-bottom pb-4 mt-2">
          <div class="img">
            <img src="../assets/img/blog-66 (1).jpg" alt="">
          </div>
          <div class="text">
            <h6>Tips to Help You Quickly Prepare your Lunch</h6>
            <span>January 12, 2019</span>
          </div>
        </div>

        <div class="d-flex border-bottom pb-4 mt-2">
          <div class="img">
            <img src="../assets/img/blog-67.jpg" alt="">
          </div>
          <div class="text">
            <h6>Why should i buy a smartwatch?</h6>
            <span>January 12, 2019</span>
          </div>
        </div>

        <div class="d-flex border-bottom pb-4 mt-2">
          <div class="img">
            <img src="../assets/img/blog-68.jpg" alt="">
          </div>
          <div class="text">
            <h6>The best augmented reality smartglasses</h6>
            <span>January 12, 2019</span>
          </div>
        </div>

        <div class="d-flex border-bottom pb-4 mt-2">
          <div class="img">
            <img src="../assets/img/blog-69.jpg" alt="">
          </div>
          <div class="text">
            <h6>12 healthiest Foods to Eat for Breakfast</h6>
            <span>January 12, 2019</span>
          </div>
        </div>
      </div>

      <div class="col-4">
        <h6 class="featured-posts-title">FEATURED POSTS</h6>
        <div class="featured-posts-img mt-4">
            <div>
                <p>RECIPES</p>
                <h5>Tips to Help You Quickly Prepare your Lunch</h5> 
            </div>
        </div>

        <h6 class="featured-author-title">FEATURED AUTHOR</h6>
        <div class="d-flex">
          <div class="featured-author-img">
            <img src="../assets/img/avatar.jpg" alt="">
          </div>
          <div class="text">
            <h5>John Doe</h5>
            <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</span>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- /Header footer -->
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

  .jumbo .container .row .col-4{
    height: 200px;
    width: 400px;
    color: white;
    font-weight: 600;
    display: flex;
    align-items: flex-end;
  }
    /* Cards */
    .hover:hover{
      border: 10px solid white;
    }

    .a {
      background-image: url(../assets/img/blog-46.jpg);
      background-position: center;
      background-size: cover;
      background-repeat: no-repeat;
      
    }

    .b {
      background-image: url(../assets/img/blog-47.jpg);
      background-position: center;
      background-size: cover;
      background-repeat: no-repeat;
      
    }

    .c {
      background-image: url(../assets/img/blog-48.jpg);
      background-position: center;
      background-size: cover;
      background-repeat: no-repeat;
      
    }

    .d {
      background-image: url(../assets/img/blog-49.jpg);
      background-position: center;
      background-size: cover;
      background-repeat: no-repeat;
      
    }

    .e {
      background-image: url(../assets/img/blog-50.jpg);
      background-position: center;
      background-size: cover;
      background-repeat: no-repeat;
      
    }

    .f {
      background-image: url(../assets/img/blog-51.jpg);
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
    
  /* HEADER FOOTER */
.header-footer{
margin-top: 2em;
}

.img{
width: 70px;
height: 70px;

}

.img img{
max-width: 100%;
}

.text{
margin-left: .5rem;
}

.featured-posts-title{
    margin-bottom: 4rem;
}

.featured-posts-img{
    background-image: url(../assets/img/blog-66.jpg);
    height: 200px;
    width: 100%;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    color: white;
    font-weight: 600;
    display: flex;
    align-items: flex-end;
    padding: .5em;
}

.featured-posts-img div p{
    background-color: #0088cc;
    width: 35%;
    text-align: center;
    padding: .3em;
}

.featured-posts-img div h5{
    font-weight: 700;
}

.featured-author-title{
    margin-top: 4rem;
}

.featured-author-img{
    height: 150px;
    width: 150px;
    
}

.featured-author-img img{
    max-width: 100%;
}
</style>
