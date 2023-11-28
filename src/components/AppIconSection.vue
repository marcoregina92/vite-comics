<script>
export default {
    name: "AppIconSection",
    data() {
        return {

        }
    }
}
</script>


<template>
    <section class="iconSection">
        <div class="container d-flex align-items-center p-5">
            <div class="sectionCard">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span class="px-3 text-white">DIGITAL COMICS</span>
            </div>

            <div class="sectionCard">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <span class="px-3 text-white">DC MERCHANDISE</span>
            </div>

            <div class="sectionCard">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span class="px-3 text-white">SUBSCRIPTION</span>
            </div>

            <div class="sectionCard">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span class="px-3 text-white">COMIC SHOP LOCATOR</span>
            </div>

            <div class="sectionCard">
                <img class="debugImg" src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span class="px-3 text-white">DC POWER VISA</span>
            </div>

        </div>
    </section>
</template>


<style scoped>
.iconSection {
    background-color: #0282f9;
}

.sectionCard {
    width: 20%;
}

img {
    height: 65px;
}

.debugImg {
    height: 47px;
}

span {
    font-size: 12px;
}
</style>