<script>
export default {
    name: "AppTopFooter",
    data() {
        return {

        }
    }
}
</script>


<template>
    <section>
        <div class="container-fluid p-5 d-flex justify-content-around">
            <div class="d-flex">
                <ul>
                    <h5 class="text-white">DC COMICS</h5>
                    <li class="text-white">Characters</li>
                    <li class="text-white">Comics</li>
                    <li class="text-white">Movies</li>
                    <li class="text-white">TV</li>
                    <li class="text-white">Games</li>
                    <li class="text-white">Videos</li>
                    <li class="text-white">News</li>
                    <ul class="text-white ps-0 pt-2">
                        <h5>SHOP</h5>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </ul>
                <ul>
                    <h5 class="text-white">DC</h5>
                    <li class="text-white"><a href="#">Terms Of Use</a></li>
                    <li class="text-white"><a href="#">Privacy policy (New)</a></li>
                    <li class="text-white"><a href="#">Ad Choices</a></li>
                    <li class="text-white"><a href="#">Advertising</a></li>
                    <li class="text-white"><a href="#">Jobs</a></li>
                    <li class="text-white"><a href="#">Subscriptions</a></li>
                    <li class="text-white"><a href="#">Talent Workshops</a></li>
                    <li class="text-white"><a href="#">CPSC Certificates</a></li>
                    <li class="text-white"><a href="#">Ratings</a></li>
                    <li class="text-white"><a href="#">Shop Help</a></li>
                    <li class="text-white"><a href="#">Contact Us</a></li>
                </ul>
                <ul>
                    <h5 class="text-white">SITES</h5>
                    <li class=""><a href="#">DC</a></li>
                    <li class=""><a href="#">MAD Magazine</a></li>
                    <li class=""><a href="#">DC Kids</a></li>
                    <li class=""><a href="#">DC Universe</a></li>
                    <li class=""><a href="#">DC Power Visa</a></li>
                </ul>
            </div>

            <div>
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </section>
</template>


<style scoped>
section {
    background-image: url(../assets/img/footer-bg.jpg);
    height: 400px;

}

ul {
    list-style-type: none;
    font-size: 13px;
}

h5 {
    font-size: 15px;
    font-weight: 800;
}

a {
    text-decoration: none;
    color: white;
}

img {
    position: relative;
    bottom: 137px;
    width: 513px;
    background-size: ;
}
</style>