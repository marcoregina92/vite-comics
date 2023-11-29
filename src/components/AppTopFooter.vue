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
        <div class="container-fluid d-flex justify-content-around">
            <div class="footerLinks d-flex p-5">
                <ul>
                    <h5 class="text-white">DC COMICS</h5>
                    <li class="text-white"><a href="#">Characters</a></li>
                    <li class="text-white"><a href="#">Comics</a></li>
                    <li class="text-white"><a href="#">Movies</a></li>
                    <li class="text-white"><a href="#">TV</a></li>
                    <li class="text-white"><a href="#">Games</a></li>
                    <li class="text-white"><a href="#">Videos</a></li>
                    <li class="text-white"><a href="#">News</a></li>
                    <ul class="text-white ps-0 pt-2">
                        <h5>SHOP</h5>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
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

            <div class="logoDc"></div>
        </div>
    </section>
</template>


<style scoped>
section {
    display: flex;
    background-image: url(../assets/img/footer-bg.jpg);
    height: 400px;
}

.footerLinks {
    width: 30%;
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
    color: grey;
}

.logoDc {
    width: 30%;
    background-size: cover;
    background-position: center;
    background-image: url("../assets/img/dc-logo-bg.png");
}
</style>