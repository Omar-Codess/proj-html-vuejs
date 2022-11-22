<script>
export default {
    name: "AppFooter"
}
</script>

<template>
    <footer>
        <div class="footer-top">
            <div class="container">
                <div class="row">

                    <div class="col-3 first">
                        <h6 class="white">ABOUT THE BLOG</h6>
                        <p class="gray">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Facilis iusto, officia dolore architecto deserunt sed incidunt, reiciendis quisquam quod aliquid voluptatum corrupti numquam!</p>
                        <p class="gray">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequatur delectus porro beatae consectetur asperiores saepe nesciunt id.</p>
                        <h6 class="white">VIEW MORE ></h6>
                    </div>

                    <div class="col-3 second">
                        <h6 class="white">RECENT POSTS</h6>

                        <div class="d-flex">
                            <div class="round-img me-4">
                                <img src="../assets/img/our-office-4-square.jpg" alt="">
                            </div>
                            <div clas="col-3-text">
                                <p class="lightgray">Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                                <span class="gray">12:53 AM Dec 19th</span>
                            </div>
                        </div>

                        <div class="d-flex mt-4">
                            <div class="round-img me-4">
                                <img src="../assets/img/our-office-5-square.jpg" alt="">
                            </div>
                            <div clas="col-3-text">
                                <p class="lightgray">Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                                <span class="gray">12:53 AM Dec 19th</span>
                            </div>
                        </div>
                    </div>

                    <div class="col-3 third">
                        <h6 class="white">RECENT COMMENTS</h6>
                        <p><span class="lightblue">></span><span class="lightgray">John Doe commented on</span> <span class="lightblue">lorem ipsum dolor sit amet.</span></p>
                        <span class="gray">12:55 AM Dec 19th</span>
                        <p class="mt-5"><span class="lightblue">></span><span class="lightgray">John Doe commented on</span> <span class="lightblue">lorem ipsum dolor sit amet.</span></p>
                        <span class="gray">12:55 AM Dec 19th</span>
                    </div>

                    <div class="col-3">
                        <h6 class="white">CATEGORIES</h6>
                        <div class="mb-2">
                            <span class="footer-categories">GADGETS</span>
                            <span class="footer-categories">PHOTOGRAPHY</span>
                        </div>
                        <div class="mb-2">
                            <span class="footer-categories">LIFESTYLE</span>
                            <span class="footer-categories">FASHION</span>
                            <span class="footer-categories">RECIPES</span>
                        </div>
                        <div class="mb-2">
                            <span class="footer-categories">TRAVEL</span>
                            <span class="footer-categories">BUSINESS</span>
                        </div>
                        <div class="mb-2">
                            <span class="footer-categories">ARCHITECTURE</span>
                            <span class="footer-categories">REVIEWS</span>
                        </div>
                        <div class="mb-2">
                            <span class="footer-categories">SPORTS</span>
                            <span class="footer-categories">VIDEOS</span>
                            <span class="footer-categories">TECHNOLOGY</span>
                        </div>
                        <div>
                            <span class="footer-categories">DESIGN</span>
                        </div>

                    </div>

                </div>
            </div>
        </div>


        <div class="footer-bottom">
            <div class="container d-flex align-items-center justify-content-between p-relative">

                <i class="fa-solid fa-chevron-up"></i>

                <div class="footer-logo">
                    <img class="me-5" src="../assets/img/logo-footer.png" alt="">
                    <span class="gray"><i class="fa-regular fa-copyright"></i> Copyright 2020. All Rights Reeserved.</span>
                </div>
                <div class="gray">
                    <span class="me-2">> FAQ's</span>
                    <span class="me-2"> > Sitemap</span>
                    <span> > Contact Us</span>
                </div>
            </div>
        </div>
    </footer>
</template>

<style>
.footer-top{
    background-color: #212529;
}

.white{
    color: white;
} 

.gray{
    color: gray;
} 

.lightgray{
    color: lightgray;
}

.lightblue{
    color: #0088cc;
}

.round-img{
    height: 80px;
    width: 150px;
    border-radius: 50%;
}

.round-img img{
    max-width: 100%;
    height: 80px;
    width: 150px;
    border-radius: 50%;
}

.footer-categories{
    color: white;
    background-color: black;
    padding: .3rem;
    font-size: 12px;
    height: 20px;
    line-height: 10px;
    margin-right: .5rem;
}

.footer-bottom{
    background-color: #1c2023;
    min-height: 100px;
}

.footer-logo{
    filter: grayscale(100%);

}

.footer-logo img{
    height: 50px;
}

.container.d-flex.align-items-center {
    min-height: 100px;
}

.fa-chevron-up{
    background-color: #373839;
    color: white;
    padding: .8rem;
    position: absolute;
    bottom: -4906px;
    right: 0;
}
</style>
