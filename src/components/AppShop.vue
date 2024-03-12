<script>

export default {

name: "AppShop",

}

</script>

<template>

<div id="carouselExampleFade" class="carousel slide carousel-fade">
  <div class="carousel-inner">
    <div class="carousel-item active">

        <div class="container-fluid">

            <div class="row">

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
    </div>
    </div>
    <div class="carousel-item">
      
        <div class="container-fluid">

<div class="row">

    <div class="col-3 shop-item">
<img src="../../public/img/01-768x768.jpg">
<div class="item-list">
<i class="fa-solid fa-star"></i> <i class="fa-solid fa-star"></i> <i class="fa-solid fa-star"></i> <i class="fa-solid fa-star"></i> <i class="fa-regular fa-star"></i>

<p>Joystick Joy Plus</p>

<div class="item-price"><span class="real-price">€120.00</span></div>
</div>
</div>

<div class="col-3 shop-item">
<img src="../../public/img/05-768x768.jpg">
<div class="item-list">
    <i class="fa-solid fa-star"></i> <i class="fa-solid fa-star"></i> <i class="fa-solid fa-star"></i> <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i>

<p>Vr Visual Set</p>

<div class="item-price"><span class="real-price">€83.00 - €118.00</span></div>
</div>
</div>

<div class="col-3 shop-item">
<img src="../../public/img/07-768x768.jpg">
<div class="item-list">
    <i class="fa-solid fa-star"></i> <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i>

<p>Joystick Camo Light</p>

<div class="item-price"><span class="real-price">€80.00 - €95.00</span></div>
</div>
</div>

<div class="col-3 shop-item">
<img src="../../public/img/14-768x768.jpg">
<div class="item-list">
<i class="fa-solid fa-star"></i> <i class="fa-solid fa-star"></i> <i class="fa-solid fa-star"></i> <i class="fa-regular fa-star"></i> <i class="fa-regular fa-star"></i>

<p>Earphones Viper X7</p>

<div class="item-price"><span class="real-price">€120.00</span></div>
</div>
</div>
</div>
</div>

    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
  
</template>

<style lang="scss">

@use '../styles/variables' as *;

.container-fluid {
    .row {
        .shop-item {
            img {
                width: 100%;
            }
            .item-list {
            background-color: rgba(0, 0, 0, 0.233);
            color: white;
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
}

/* .shop-container {
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
} */



</style>