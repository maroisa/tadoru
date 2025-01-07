<script setup>
import { inject } from 'vue';

const sidenavActive = inject("sidenavActive")

</script>

<template>
    <div v-show="sidenavActive">
        Sidebar
    </div>
</template>