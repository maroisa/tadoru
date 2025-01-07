<script setup>
import TopNav from "./components/TopNav.vue"
import Content from "./components/Content.vue"
import { provide, ref } from "vue";

const sidenavActive = ref(false);
provide("sidenavActive", sidenavActive)

</script>

<template>
    <TopNav />
    <Content />
</template>