<script>

export default {

name: "AppNav",

props: {
        links: Array,
    },

    data() {
    return {
      isDropdownOpen: false
    };
  },
  methods: {
    toggleDropdown() {
      this.isDropdownOpen = true;
    },
    closeDropdown() {
      this.isDropdownOpen = false;
    },
    keepDropdownOpen() {
      
    }
  }

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

                    <div class="dropdown">
                        <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false" v-for="link in links">
                        {{ link }}
                        </button>
                    <ul class="dropdown-menu dropdown-menu-dark">
                        <li><a class="dropdown-item active" href="#">Action</a></li>
                        <li><a class="dropdown-item" href="#">Another action</a></li>
                        <li><a class="dropdown-item" href="#">Something else here</a></li>
                        <li><hr class="dropdown-divider"></li>
                        <li><a class="dropdown-item" href="#">Separated link</a></li>
                    </ul>
                </div>
                    
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
            button {
                background-color: transparent;
                border: none;
                margin-right: 40px;
            }
            .dropdown-menu.dropdown-menu-dark {
                background-color: $primarycolor;
                border: 1px solid grey;
            }
            .dropdown-toggle::after {
                display: none;
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