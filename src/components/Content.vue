<script setup>
import Editor from "./Editor.vue"
import SideNav from "./SideNav.vue"

</script>

<template>
    <main class="grow">
        <SideNav />
        <Editor />
    </main>
</template>

<style scoped>

.grow { overflow-y: auto; }

</style>