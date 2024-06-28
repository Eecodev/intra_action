<template>
    <div class="container d-flex justify-content-end">
        Copyright 2024 by emenser.
    </div>
</template>

<script>
    export default {
        name: 'Footer',
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;

    div{
        background-color: $color-green;
        border: 2px solid $color-white;
        border-radius: 20px;
        padding: 0.5rem;
    }

</style>