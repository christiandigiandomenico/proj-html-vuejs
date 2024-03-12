<script>

import AppShop from './AppShop.vue'

export default {

name: "AppMain",

components: {
  AppShop,
}

}

</script>

<template>

    <main>
  
        <div class="main-container">

            <section>

            <div class="shop-methods">

            <div class="shop-container">

                <img src="../../public/img/delivery.png">

                <div class="delivery-container">

                    <div class="shop-bold">Free Delivery</div>

                    <div class="free-delivery-two">Free Shipping On All Orders</div>

                </div>

            </div>

            <div class="divider"></div>

            <div class="shop-container">

                <img src="../../public/img/money.png">

                <div class="money-container">

                    <div class="shop-bold">Money Return</div>

                    <div class="money-two">Back Guarantee in 7 Days</div>

                </div>

            </div>

            <div class="divider"></div>

            <div class="shop-container">

                <img src="../../public/img/percentage.png">

                <div class="percentage-container">

                    <div class="shop-bold">Member Discount</div>

                    <div class="percentage-two">On every order over €130.00</div>

                </div>

            </div>

            <div class="divider"></div>

            <div class="shop-container">

                <img src="../../public/img/payment.png">

                <div class="payment-container">

                    <div class="shop-bold">Return Policy</div>

                    <div class="payment-two">Support 24 hours a day</div>

                </div>

            </div>

            </div>

        </section>

        <section>

            <div class="container-fluid">

                <div class="row">
                    
                    <div class="col-6 popular-game">
                        <img src="../../public/img/cms-banner-01.jpg">

                        <div class="popular-container">

                            <div class="most-popular">Most Popular</div>

                            <div class="game-title-popular">The Battlefield 4
                            <br>Naval Strike</div>

                        </div>
                    </div>

                    <div class="col-6 popular-game">
                        <img src="../../public/img/cms-banner-02.jpg">

                        <div class="popular-container">

                            <div class="most-popular">Latest Game</div>

                            <div class="game-title-popular">Assassin's Creed <br>
                            Unity Game</div>

                        </div>
                    </div>

                </div>

            </div>

        </section>

        <section>

            <div class="special-category-container">

                <div class="title-special">Special Category</div>

                <div class="divider-special"></div>

            </div>

            <div class="container-fluid shop-game-container">

                <div class="row">

                    <div class="col-4 shop-game">
                        <img src="../../public/img/category-image-02-446x550_t.jpg">

                        <div class="shop-now">
                            <div class="shop-now-title">
                                Batman
                            </div>
                            <div class="shop-now-now">
                                <a href="#">Shop Now</a>
                            </div>
                        </div>
                    </div>

                    <div class="col-4 shop-game">
                        <img src="../../public/img/category-image-01-446x550_t.jpg">

                        <div class="shop-now">
                            <div class="shop-now-title">
                                Bayonetta
                            </div>
                            <div class="shop-now-now">
                                <a href="#">Shop Now</a>
                            </div>
                        </div>
                    </div>

                    <div class="col-4 shop-game">
                        <img src="../../public/img/category-image-03-446x550_t.jpg">

                        <div class="shop-now">
                            <div class="shop-now-title">
                                Dark Souls
                            </div>
                            <div class="shop-now-now">
                                <a href="#">Shop Now</a>
                            </div>
                        </div>
                    </div>

                </div>

            </div>

        </section>

        <section>

                <div class="our-products-container">

                    <div class="title-special">Our Products</div>

                    <div class="divider-special"></div>

                </div>

                <div class="product-selection">

                    <span>Featured</span>

                    <span>New Arrival</span>

                    <span>Best Sellers</span>

                </div>

                <AppShop></AppShop>

                <div class="container-fluid discount-games">

                    <div class="row">

                        <div class="col-6 popular-game">
                            <img src="../../public/img/cms-banner-01.jpg">

                            <div class="popular-container">

                                <div class="most-popular">Most Popular</div>

                                <div class="game-title-popular">The Battlefield 4
                                <br>Naval Strike</div>

                            </div>
                        </div>

                        <div class="col-6 popular-game">
                            <img src="../../public/img/cms-banner-01.jpg">

                            <div class="popular-container">

                                <div class="most-popular">Most Popular</div>

                                <div class="game-title-popular">The Battlefield 4
                                <br>Naval Strike</div>

                            </div>
                        </div>

                    </div>

                </div>

        </section>

        </div>

    </main>

</template>

<style lang="scss">

@use '../styles/variables' as *;

section {
    max-width: 1400px;
    margin: auto;
}

.main-container {
    background-image: url(../../public/img/body-bg.jpg);
}

.shop-methods {
    padding-top: 90px;
    padding-bottom: 90px;
    display: flex;
    justify-content: space-between;
    flex-wrap: nowrap;
    color: white;
    .divider {
        border-right: 1px solid rgba(158, 158, 158, 0.479);
    }
    .shop-container {
        display: flex;
        align-items: center;
        gap: 20px;
        img {
            width: 57px;
            height: 40px;
        }
        .shop-bold {
            font-weight: bold;
        }
    }
}

.container-fluid {
    .popular-game {
        position: relative;
        margin-bottom: 100px;
        .popular-container{
            position: absolute;
            top: 100px;
            right: 100px;
            .game-title-popular {
                font-size: 42px;
                font-weight: bold;
                color: white;
            }
            .most-popular {
                font-size: 26px;
                font-weight: bold;
                background-color: $secondarycolor;
                display: inline-block;
                transform: skewX(-15deg);
                padding: 0px 10px;
                margin-bottom: 30px;
            }
        }
    }
}
    .title-special {
        font-size: 28px;
        color: white;
        text-align: center;
        font-weight: bold;
        margin-bottom: 25px;
    }
    .divider-special {
        border-bottom: 2px solid $secondarycolor;
        width: 50px;
        margin: auto;
        margin-bottom: 30px;
    }

.shop-game-container {
    .shop-game {
        position: relative;
        margin-bottom: 100px;
        .shop-now {
            background-color: rgba(0, 0, 0, 0.466);
            padding: 20px;
            width: 446px;
            position: absolute;
            left: 12px;
            bottom: 0;
            .shop-now-title {
                color: white;
                font-size: 20px;
                font-weight: bold;
            }
            .shop-now-now {
                a {
                    color: $secondarycolor;
                }
            }
        }
    }
}

.product-selection {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 40px;
    span {
        text-align: center;
        border: 1px solid rgba(161, 161, 161, 0.562);
        width: 180px;
        padding: 20px 30px;
        color: white;
        font-weight: bold;
    }
}

.discount-games {
    margin-top: 100px;
}

</style>