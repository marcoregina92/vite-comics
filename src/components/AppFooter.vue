<script>

import AppTopFooter from "../components/AppTopFooter.vue";
import AppBottomFooter from "../components/AppBottomFooter.vue";


export default {
    name: "AppFooter",
    data() {
        return {};
    },
    components: { AppTopFooter, AppBottomFooter }
}
</script>


<template>
    <footer>
        <AppTopFooter />
        <AppBottomFooter />
    </footer>
</template>


<style scoped></style>