<script>

export default {

name: "AppJumbo",

}

</script>

<template>

    <div class="jumbo">

        <div class="jumbo-container">

            <div class="upcoming-stock">Upcoming Stock</div>

            <div class="game-title"><span>Resident Evil 3
                <br>Remake</span></div>

            <div class="button-shop"><button>Shop Now</button></div>

        </div>

    </div>
  
</template>

<style lang="scss">

@use '../styles/variables' as *;

.jumbo {
    height: 900px;
    background-image: url(../../public/img/jumbotron.jpg);
    background-size: cover;
    position: relative;

    .jumbo-container{

        position: absolute;
        left: 250px;
        top: 200px;

    .upcoming-stock {
        font-size: 26px;
        font-weight: bold;
        background-color: $secondarycolor;
        display: inline-block;
        transform: skewX(-15deg);
        padding: 5px 20px;
        margin-bottom: 30px;
    }

    .game-title {
        font-size: 46px;
        font-weight: bold;
        color: white;
        margin-bottom: 100px;
    }

    .button-shop {
        button {
            background-color: white;
            border: none;
            color: black;
            padding: 15px 25px;
            font-weight: bold;
        }
        button:hover {
            background-color: $secondarycolor;
        }
    }
    }
}

</style>