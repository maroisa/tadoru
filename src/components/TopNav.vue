<template>
    <header class="row">
        <button>LEFT</button>
        <h2>Tadoru</h2>
    </header>
</template>

<style scoped>

* {
    background-color: rgb(62, 68, 73);
}

.row {
    min-height: 64px;
    align-items: center;
    gap: 1rem;
    box-shadow: 0 0 2rem rgba(0, 0, 0, 0.25);
    z-index: 3;
}

button {
    border: none;
    height: 100%;
    width: 64px;
}

</style>