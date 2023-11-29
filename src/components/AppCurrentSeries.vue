<script>

export default {
    name: "AppCurrentSeries",
    props: {
        products: Object

    },
    components: {}

}
</script>


<template>
    <section>
        <div class="titleCurrentSeries">
            CURRENT SERIES
        </div>
        <div class="d-flex flex-wrap container p-5">

            <div v-for="product in products" class="cards">
                <img :src="product.thumb" alt="">
                <p class="text-uppercase"> {{ product.series }}</p>

            </div>

            <div class="more text-white">
                LOAD MORE
            </div>
        </div>
    </section>
</template>


<style scoped>
section {
    background-color: #1c1c1c;
}


.titleCurrentSeries {
    color: white;
    padding: 10px;
    background-color: #0282f9;
    width: 144px;
    position: relative;
    top: -14px;
    left: 281px;
    font-size: 12px;
    font-weight: 800;
    text-align: center;
}

.cards {
    width: calc(100% / 6);
}

img {
    width: 150px;
    height: 150px;
    object-position: top;
    object-fit: cover;
    cursor: pointer;
}

img:hover {
    box-shadow: 0 0 11px rgba(255, 255, 255, 0.277);
}

p {
    color: white;
    font-size: 10px;
    font-weight: 800;
    text-align: start;
    padding-top: 10px;
}

.more {
    position: relative;
    left: 548px;
    width: 120px;
    background-color: #0282f9;
    padding: 10px;
    font-weight: bold;
}
</style>