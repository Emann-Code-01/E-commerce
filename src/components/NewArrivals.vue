<script setup>
    import vector8 from "../assets/vector8.svg";
</script>

<template>
    <div class="card">
        <div class="header">
            <h1>New Arrivals</h1>
            <img :src="vector8" alt="Vector Image">
        </div>
    </div>
</template>

<style scoped>
.card {
    margin: 2em 3em;
    letter-spacing: 1px;
}

.header {
    display: flex;
    align-items: center;
    gap: 1em;
}

h1 {
    font-weight: 700;
}
</style>