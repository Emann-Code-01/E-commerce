<script setup>
import Pic1 from "../assets/BrandPic/Rectangle 36.svg"
import Pic2 from "../assets/BrandPic/Rectangle 44.svg"
import Pic3 from "../assets/BrandPic/Rectangle 38.svg"
import Pic4 from "../assets/BrandPic/Rectangle 45.svg"
import Pic5 from "../assets/BrandPic/Rectangle 43.svg"
import Pic6 from "../assets/BrandPic/Rectangle 41.svg"
</script>

<template>
    <div class="brand">
        <span class="img-1">
            <img :src="Pic1" alt="H&M">
        </span>
        <span class="img-2">
            <img :src="Pic2" alt="Obey">
        </span>
        <span class="img-3">
            <img :src="Pic3" alt="Obey">
        </span>
        <span class="img-4">
            <img :src="Pic4" alt="Obey">
        </span>
        <span class="img-5">
            <img :src="Pic5" alt="Obey">
        </span>
        <span class="img-6">
            <img :src="Pic6" alt="Obey">
        </span>
    </div>
</template>

<style scoped>
.brand {
    display: flex;
    margin-top: 50px;
    background: #EBD96B;
    width: 100%;
    height: auto;
    padding: 30px 20em;
    gap: 6em;
}

.img-1 {
    display: flex;
    margin-bottom: -3px;
    /*Use the line of code direct below to remove image background. U can use either "multiply" or "darken" both work for removing background*/
    mix-blend-mode: multiply;
}

.img-2 {
    display: flex;
    margin-bottom: -8px;
    mix-blend-mode: multiply;
}

.img-3 {
    display: flex;
    margin-bottom: -10px;
    mix-blend-mode: multiply;
}

.img-4 {
    mix-blend-mode: multiply;
}

.img-5 {    
    display: flex;
    margin-bottom: -5px;
    mix-blend-mode: multiply;
}

.img-6 {
    display: flex;
    margin-bottom: -20px;
    mix-blend-mode: multiply;
}

@media (max-width: 768px) {
    .brand {
        gap: 3em;
        padding: 30px 60px;
    }

    .img-2 {
        display: flex;
        margin-top: -6px;
    }

    .img-3 {
        display: flex;
        margin-top: -5px;
    }

    .img-4 {
        display: flex;
        margin-top: -3px;
    }

    .img-6 {
        display: flex;
        margin-top: -11px;
    }
}

/*@media (max-width: 480px) {
    .brand {

    }    
}*/
</style>