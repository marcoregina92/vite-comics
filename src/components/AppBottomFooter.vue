<script>
export default {
    name: "AppBottomFooter",
    data() {
        return {

        }
    }
}
</script>


<template>
    <section>
        <div class="container d-flex justify-content-between align-items-center h-100">
            <div>
                <button class="btn btn-outline-light">SIGN-UP NOW!</button>
            </div>
            <div class="d-flex align-items-center">

                <h5>FOLLOW US</h5>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
            </div>
        </div>

    </section>
</template>
<style scoped>
section {
    background-color: #303030;
    height: 140px;
}

button {
    border-color: #0282f9;
    border-radius: 0;
    padding: 10px;
}

h5 {
    margin: 0;
    color: #0282f9;
    font-weight: bold;
    padding-right: 20px;
}

img {
    padding-right: 10px;
}
</style>