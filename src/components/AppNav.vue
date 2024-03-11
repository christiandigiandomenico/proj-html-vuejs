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

                    <i class="fa-solid fa-magnifying-glass"></i>

                    <i class="fa-regular fa-user"></i>

                    <span><i class="fa-solid fa-bag-shopping"></i>
                        (0)€0.00
                    </span>

                </div>

            </div>

        </div>

    </nav>
  
</template>

<style lang="scss">

nav {
    background-color: #1d1427;

    .nav-container {
        max-width: 1400px;
        margin: auto;

        .superior-nav {
        
        display: flex;
        justify-content: space-between;
        padding: 15px;
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
        }
    }
    }
}

</style>