<script setup>
import { inject } from 'vue';

const sidenavActive = inject("sidenavActive")

</script>

<template>
    <div class="container" :class="sidenavActive ? 'active': ''">
        Sidebar
    </div>
</template>

<style scoped>

/* TODO: fix animation */
.container {
    position: sticky;
    visibility: hidden;
    width: 0;
    background-color: grey;
    transition: all 500ms;
}

.active {
    visibility: visible;
    width: 200px;
}

</style>