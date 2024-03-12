<script>

export default {

name: "AppFooter",

props: {
        linksfooter: Array,
        linksfooter2: Array,
    },

}

</script>

<template>

<footer>

    <div class="footer-container">

        <div class="address-info">
            <div class="address-info-title">Address Info</div>

            <div class="address-info-information"><i class="fa-solid fa-location-dot"></i> 60 29th Street San Francisco, CA 94110
            <br>507-Union Trade Center, United States of
            <br>America</div>

            <div class="address-info-telephone"><i class="fa-solid fa-phone"></i> (+00) 123-456-789</div>

            <div class="address-info-mail"><i class="fa-solid fa-envelope"></i> demo@example.com</div>

        </div>

        <div class="footer-information">
            <div class="address-info-title">Information</div>

            <ul>
                <li v-for="link in linksfooter">{{ link }}</li>
            </ul>

        </div>

        <div class="footer-extras">
            <div class="address-info-title">Extras</div>
            
            <ul>
                <li v-for="link2 in linksfooter2">{{ link2 }}</li>
            </ul>
        </div>

        <div class="footer-newsletter">

            <div class="address-info-title">Our Newsletter</div>

            <p>There are many variations of passages of form humour or randomised</p>

            <input type="text" placeholder="Inserisci la tua mail">

            <div class="footer-socials"><i class="fa-brands fa-facebook-f"></i> <i class="fa-brands fa-twitter"></i> <i class="fa-brands fa-google-plus-g"></i> <i class="fa-brands fa-skype"></i> <i class="fa-brands fa-instagram"></i></div>

        </div>

    </div>

    <hr>

    <div class="copyright-payment">

        <div class="copyright">
            Copyright © 2023 Codezeel
        </div>

        <div class="payment">
            <img src="../../public/img/card-visa.png">

            <img src="../../public/img/card-mastercard.png">

            <img src="../../public/img/card-mastercard2.png">

            <img src="../../public/img/card-paypal.png">

            <img src="../../public/img/card-multicolor.png">

        </div>

    </div>

</footer>
  
</template>

<style lang="scss">

@use '../styles/variables' as *;

footer {
    background-image: url(../../public/img/footer-bg.png);
}

.footer-container {
    padding-top: 100px;
    padding-bottom: 60px;
    display: flex;
    margin: auto;
    gap: 150px;
    max-width: 1400px;
    .address-info {
        i {
            color: $secondarycolor;
            margin-right: 10px;
        }
        color: rgba(255, 255, 255, 0.541);
        .address-info-information, .address-info-telephone {
            margin-bottom: 20px;
        }
    }
}

.address-info-title {
            font-size: 24px;
            font-weight: bold;
            color: white;
            margin-bottom: 20px;
        }

.footer-information {
    ul {
        list-style-type: none;
        color: rgba(255, 255, 255, 0.541);
        padding: 0;
        li {
            margin-bottom: 10px;
        }
    }
}

.footer-extras {
    ul {
        list-style-type: none;
        color: rgba(255, 255, 255, 0.541);
        padding: 0;
        li {
            margin-bottom: 10px;
        }
    }
}

.footer-newsletter {
    p {
        color: rgba(255, 255, 255, 0.541);
    }
    input {
        width: 100%;
        background-color: white;
        border: none;
        padding: 10px;
        color: black;
        margin-bottom: 20px;
    }
    .footer-socials {
        color: white;
        i {
            margin-right: 20px;
        }
    }
}

hr {
    border-color: white;
}

.copyright-payment {
    max-width: 1400px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    .copyright {
        color: rgba(255, 255, 255, 0.541);
    }
    .payment {
        img {
            margin-right: 10px;
        }
    }
}

.footer-information{
    li:hover {
        color: $secondarycolor;
    }
}

.footer-extras {
    li:hover {
        color: $secondarycolor;
    }
}

.footer-newsletter {
    .footer-socials {
        i:hover {
            color: $secondarycolor;
        }
    }
}

</style>