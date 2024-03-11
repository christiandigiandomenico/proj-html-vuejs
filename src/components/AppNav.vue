<script>

export default {

name: "AppNav",

props: {
        links: Array,
    },

}

</script>

<template>

    <nav>

        <div class="nav-container">

            <div class="superior-nav">

                <div class="superior-nav-left">

                    <span>Wishlist(0)</span>

                    <span>Need Help? <i class="fa-solid fa-chevron-down"></i></span>

                </div>

                <div class="superior-nav-right">

                    <span>Call 24/7 .800-8754-987</span>

                </div>

            </div>

            <hr>

            <div class="lower-nav">

                <div class="lower-nav-left">
                    <img src="../../public/img/logo.png">
                </div>

                <div class="lower-nav-center">
                    <ul>
                        <li v-for="link in links">{{ link }}</li>
                    </ul>
                </div>

                <div class="lower-nav-right">

                    <img src="../../public/img/finder.png">

                    <img src="../../public/img/user.png">

                    <span><img src="../../public/img/shop.png">
                        (0)€0.00
                    </span>

                </div>

            </div>

        </div>

    </nav>
  
</template>

<style lang="scss">

@use '../styles/variables' as *;

nav {
    background-color: $primarycolor;

    .nav-container {
        max-width: 1400px;
        margin: auto;

        .superior-nav {
        
        display: flex;
        justify-content: space-between;
        padding-top: 10px;
        color: gray;

        .superior-nav-left {
            display: flex;
            gap: 20px;
        }
    }
    .lower-nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding-bottom: 20px;
        padding-top: 10px;
        color: white;
        .lower-nav-left {
            display: flex;
            align-items: center;
        }
        .lower-nav-center {
            display: flex;
            align-items: center;
            ul {
                margin-bottom: 0;
                font-weight: bold;
                display: flex;
                gap: 40px;
                list-style-type: none;
            }
        }
        .lower-nav-right {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
            span {
                color: $secondarycolor;
            }
        }
    }
    }
}

</style>