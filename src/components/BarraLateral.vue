<template>
    <header>
        <h1>
            <img src="../assets/logo.png" alt="Logo">
        </h1>
    </header>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
    name: 'BarraLateral'
})
</script>

<style scoped>
header {
    background-color: black;
    width: 100%;
    height: 100vh;
    color: white;
    text-align: justify;
    padding: 1rem;
}

@media only screen and (max-width: 768px) {
header {
    padding: 2.5rem;
    height: auto;
}
}

img {
    background-color: bisque;
    width: auto;
    height: 20%;
    border: solid;
    border-color: white;
    border-radius: 5px;

}

</style>