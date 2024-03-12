<script>

import AppShop from './AppShop.vue'
import AppShop2 from './AppShop2.vue'

export default {

name: "AppMain",

components: {
  AppShop,
  AppShop2,
}

}

</script>

<template>

    <main>
  
        <div class="main-container">

            <section>

            <div class="shop-methods">

            <div class="shop-container">

                <img class="white" src="../../public/img/delivery.png">

                <img class="orange" src="../../public/img/delivery-orange.png">

                <div class="delivery-container">

                    <div class="shop-bold">Free Delivery</div>

                    <div class="free-delivery-two">Free Shipping On All Orders</div>

                </div>

            </div>

            <div class="divider"></div>

            <div class="shop-container">

                <img class="white" src="../../public/img/money.png">

                <img class="orange" src="../../public/img/money-orange2.png">

                <div class="delivery-container">

                    <div class="shop-bold">Money Return</div>

                    <div class="money-two">Back Guarantee in 7 Days</div>

                </div>

            </div>

            <div class="divider"></div>

            <div class="shop-container">

                <img class="white" src="../../public/img/percentage.png">

                <img class="orange" src="../../public/img/percentage-orange.png">

                <div class="delivery-container">

                    <div class="shop-bold">Member Discount</div>

                    <div class="percentage-two">On every order over €130.00</div>

                </div>

            </div>

            <div class="divider"></div>

            <div class="shop-container">

                <img class="white" src="../../public/img/payment.png">

                <img class="orange" src="../../public/img/payment-orange.png">

                <div class="delivery-container">

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
                            <img src="../../public/img/cms-banner-03.jpg">

                            <div class="popular-container">

                                <div class="most-popular">20% Discount</div>

                                <div class="game-title-popular">Dragon's Dogma
                                <br>Video Game</div>

                            </div>
                        </div>

                        <div class="col-6 popular-game">
                            <img src="../../public/img/cms-banner-04.jpg">

                            <div class="popular-container">

                                <div class="most-popular">30% Discount</div>

                                <div class="game-title-popular">World of Tanks
                                <br>New Game</div>

                            </div>
                        </div>

                    </div>

                </div>

        </section>

        <section>

            <div class="our-products-container">

                <div class="title-special">Deal Of The Day</div>

                <div class="divider-special"></div>

            </div>

            <div class="product-selection">

                <span>1026 Days</span>

                <span>13 Hours</span>

                <span>24 Minutes</span>

                <span>17 Seconds</span>

            </div>

            <AppShop2></AppShop2>

        </section>

        <section>

            <div class="our-team">
            <div id="carouselExampleIndicators" class="carousel slide">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      
        <div class="team-container">

<img class="our-team-quote" src="../../public/img/quote.png">

<img src="../../public/img/t5-1-100x100_left.jpg">

</div>

<div class="team-name">Luies Charles <span>(Web Designer)</span></div>

<div class="team-introduction">"There are many variations of passages of Lorem Ipsum available, but the majority of suffered alteration in some form, by injected humor. There are many variations of passages of Lorem Ipsum available, but the majority of suffered alteration in some form, by injected humor. There are many variations of passages of Lorem Ipsum available"</div>

    </div>
    <div class="carousel-item">
      
        <div class="team-container">

<img class="our-team-quote" src="../../public/img/quote.png">

<img src="../../public/img/t2-1-100x100_left.jpg">

</div>

<div class="team-name">Luies Charles <span>(Web Designer)</span></div>

<div class="team-introduction">"There are many variations of passages of Lorem Ipsum available, but the majority of suffered alteration in some form, by injected humor. There are many variations of passages of Lorem Ipsum available, but the majority of suffered alteration in some form, by injected humor. There are many variations of passages of Lorem Ipsum available"</div>

    </div>
    <div class="carousel-item">
      
        <div class="team-container">

<img class="our-team-quote" src="../../public/img/quote.png">

<img src="../../public/img/t4-1-100x100_left.jpg">

</div>

<div class="team-name">Luies Charles <span>(Web Designer)</span></div>

<div class="team-introduction">"There are many variations of passages of Lorem Ipsum available, but the majority of suffered alteration in some form, by injected humor. There are many variations of passages of Lorem Ipsum available, but the majority of suffered alteration in some form, by injected humor. There are many variations of passages of Lorem Ipsum available"</div>

    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
</div>

        </section>

        <section>

            <div class="our-products-container new-game-blogs-title">

                <div class="title-special">New Game Blogs</div>

                <div class="divider-special"></div>

            </div>

            <div class="container-fluid new-game-blogs-container">

                <div class="row">

                    <div class="col-4 new-game-blogs">
                        <img src="../../public/img/Nisi-ut-aliquid-ex-ea-com-1400x878_t.jpg">

                        <div class="new-game-sub"><i class="fa-regular fa-calendar-days"></i> <span>Jan 18, 2021</span> <i class="fa-solid fa-comments"></i> <span>0 Comment</span></div>

                        <p>Anyway REPS is a NYC agency repres enting photographers</p>
                    </div>

                    <div class="col-4 new-game-blogs">
                        <img src="../../public/img/Architecto-beatae-vitae-dicta-1400x878_t.jpg">

                        <div class="new-game-sub"><i class="fa-regular fa-calendar-days"></i> <span>May 30, 2021</span> <i class="fa-solid fa-comments"></i> <span>0 Comment</span></div>

                        <p>Nasual risus suscipit Lorem Ipsum is simply text</p>
                    </div>

                    <div class="col-4 new-game-blogs">
                        <img src="../../public/img/At-vero-eos-et-accusamus-1400x878_t.jpg">

                        <div class="new-game-sub"><i class="fa-regular fa-calendar-days"></i> <span>Apr 13, 2021</span> <i class="fa-solid fa-comments"></i> <span>0 Comment</span></div>

                        <p>Nostrum lesum Christum Lorem Ipsum is simply text</p>
                    </div>

                </div>

            </div>

        </section>

        <section>
        <div class="section-divider"></div>

                <div class="sponsor-pictures">

                    <img src="../../public/img/brand-01.png">

                    <img src="../../public/img/brand-02.png">

                    <img src="../../public/img/brand-03.png">

                    <img src="../../public/img/brand-04.png">

                    <img src="../../public/img/brand-05.png">

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
    background-size: contain;
    background-repeat: repeat;
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
    margin-top: 80px;
}

.our-team {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 90px;
    background-image: url(../../public/img/parallax.jpg);
    background-size: cover;
    .team-name {
        font-weight: bold;
        color: white;
        margin-bottom: 30px;
        span {
            color: $secondarycolor;
        }
    }
    .team-introduction {
        color: rgba(255, 255, 255, 0.527);
        text-align: center;
        margin-bottom: 50px;
        max-width: 1100px;
    }
    .team-container {
        position: relative;
        .our-team-quote {
            background-color: $secondarycolor;
            padding: 8px;
            position: absolute;
            top: 0;
            left: 495px;
        }
        img {
            border-radius: 50%;
            border: 1px solid $secondarycolor;
            margin-bottom: 30px;
            margin-top: 130px;
        }
    }
    .slider-dots {
        color: white;
        font-size: 10px;
        display: flex;
        gap: 10px;
        margin-bottom: 65px;
    }
}

.new-game-blogs-title {
    margin-top: 85px;
}

.new-game-blogs-container{

.new-game-blogs {
    p {
        color: white;
        font-weight: bold;
        font-size: 14px;
    }
    .new-game-sub {
        color: gray;
        display: flex;
        align-items: center;
        gap: 20px;
        margin-bottom: 10px;
        .fa-regular, .fa-solid {
            color: $secondarycolor;
        }
    }
    img {
        width: 100%;
        margin-bottom: 15px;
    }
}
}

.section-divider {
    border-bottom: 1px solid gray;
    width: 1400px;
    margin: auto;
    margin-top: 60px;
    margin-bottom: 60px;
}

.sponsor-pictures {
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 80px;
    padding-bottom: 60px;
}

.shop-container {
    .orange {
        display: none;
    }
}

.shop-container:hover .delivery-container .shop-bold {
    color: $secondarycolor;
}

.shop-container:hover .white {
    display: none;
}

.shop-container:hover .orange {
    display: block;
}

.team-container {
    text-align: center;
}

.team-name {
    text-align: center;
}

.carousel-indicators button {
  border-radius: 50%;
  width: 10px !important;
  height: 10px !important;
}

</style>