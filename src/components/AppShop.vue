<script>

export default {

name: "AppShop",

}

</script>

<template>

<div class="container-fluid container-shop">

<div class="row shop-container">

    <img class="arrow-left" src="../../public/img/arrow-left-white.png">

    <div class="shop-carousel">

    <div class="col-3 shop-item">
        <img src="../../public/img/04-768x768.jpg">
        <div class="item-list">
            <i class="fa-solid fa-star"></i> <i class="fa-solid fa-star"></i> <i class="fa-solid fa-star"></i> <i class="fa-solid fa-star"></i> <i class="fa-regular fa-star"></i>

            <p>Shopping Mahjong Connect</p>

            <div class="item-price"><span class="discounted-price">€180.00</span> <span class="real-price">€100.00</span></div>
        </div>
    </div>

    <div class="col-3 shop-item">
        <img src="../../public/img/09-768x768.jpg">
        <div class="item-list">
            <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i>

            <p>Buddy and Lucky Solitaire</p>

            <div class="item-price"><span class="real-price">€83.00 - €90.00</span></div>
        </div>
    </div>

    <div class="col-3 shop-item">
        <img src="../../public/img/03-768x768.jpg">
        <div class="item-list">
            <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i>

            <p>Taishou x Alice Epilogue</p>

            <div class="item-price"><span class="real-price">€60.00 - €75.00</span></div>
        </div>
    </div>

    <div class="col-3 shop-item">
        <img src="../../public/img/11-768x768.jpg">
        <div class="item-list">
            <i class="fa-solid fa-star"></i> <i class="fa-solid fa-star"></i> <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i>

            <p>Labyrinths of the World</p>

            <div class="item-price"><span class="real-price">€110.00</span></div>
        </div>
    </div>

    </div>

    <img class="arrow-right" src="../../public/img/arrow-right-white.png">

</div>

</div>
  
</template>

<style lang="scss">

@use '../styles/variables' as *;

.shop-container {
    display: flex;
    color: white;
    position: relative;

    .arrow-left {
        width: 56px;
        height: 31px;
        position: absolute;
        top: 150px;
        left: -15px;
    }
    .arrow-right {
        width: 56px;
        height: 31px;
        position: absolute;
        top: 150px;
        right: -15px;
    }

    .shop-carousel {
        display: flex;
        gap: 20px;
        img {
            width: 100%;
        }
    }
    .shop-item {
        width: calc(100% / 4 - 20px / 4 * 3);
        .item-list {
            background-color: rgba(0, 0, 0, 0.233);
            .item-price {
                    .discounted-price {
                        text-decoration: line-through;
                    }
                    .real-price {
                        color: $secondarycolor;
                    }
                }
            .fa-solid.fa-star {
                color: $secondarycolor;
                
            }
        }
    }
}



</style>