<template>
    <nav class="container">
        <ul class="d-flex list-unstyled justify-content-end m-0">
            <li><a href="#">Mahdi</a></li>
            <li><a href="#">(Intra)action</a></li>
        </ul>
    </nav>
</template>

<script>
    export default {
        name: 'Header',
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;

nav {
    background-color: $color-green;
    border: 2px solid $color-white;
    border-radius: 20px;
}
li{
    padding: 0.5rem;
}
li a{
    text-decoration: none;
    
    color: $color-black;
}
</style>