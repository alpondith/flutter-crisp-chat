<script setup lang="ts">
import { useData } from "vitepress";
const { frontmatter } = useData();
</script>

<template>
    <div v-if="frontmatter.sponsors !== false">
        <a href="https://www.buymeacoffee.com/alpondith" target="_blank">
            <img class="img" src="/graphics/advertisement/bmc.jpg" alt="buy me a coffee" />
        </a>
    </div>
</template>

<style>
.img {
    border: 1px solid #ddd;
}
</style>
