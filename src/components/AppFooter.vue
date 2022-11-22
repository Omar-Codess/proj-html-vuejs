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
                        <div>
                            <span>GADGETS</span>
                            <span>PHOTOGRAPHY</span>
                        </div>
                        <div>
                            <span>LIFESTYLE</span>
                            <span>FASHION</span>
                            <span>RECIPES</span>
                        </div>
                        <div>
                            <span>TRAVEL</span>
                            <span>BUSINESS</span>
                        </div>
                        <div>
                            <span>ARCHITECTURE</span>
                            <span>REVIEWS</span>
                        </div>
                        <div>
                            <span>SPORTS</span>
                            <span>VIDEOS</span>
                            <span>TECHNOLOGY</span>
                        </div>
                        <div>
                            <span>DESIGN</span>
                        </div>

                    </div>

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


</style>
