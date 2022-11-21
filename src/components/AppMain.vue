<script>
export default {
    name: "AppMain"
}
</script>

<template>
<!-- Categorie -->
    <div class="categories d-flex align-items-center">
        <div class="container p-relative">
            <i class="fa-solid fa-chevron-left"></i>
            <i class="fa-solid fa-chevron-right"></i>
            <div class="categories-container d-flex justify-content-evenly">
                <p class="categories-button">GADGETS</p>
                <p class="categories-button">PHOTOGRAPHY</p>
                <p class="categories-button">LIFESTYLE</p>
                <p class="categories-button">FASHION</p>
                <p class="categories-button">RECIPES</p>
                <p class="categories-button">TRAVEL</p>
            </div>
        </div>
    </div>
<!-- /Categorie -->

</template>

<style>
/* CATEGORIE */
.categories{
    background-color: #0074ad;
    height: 200px;
}

.categories-button{
    background-color: #212529;
    color: white;
    width: 15%;
    text-align: center;
    padding: .7rem;
    font-weight: 700;
}

.fa-chevron-left{
    position: absolute;
    left: 185px;
    bottom: -570px;
}

.fa-chevron-right{
    position: absolute;
    right: 185px;
    bottom: -570px;
}
</style>
