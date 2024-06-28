<template>
    <div class="main container">
        <div class="card" style="width: 18rem;">
            <ul class="list-group list-group-flush">
                <li class="list-group-item">An item</li>
                <li class="list-group-item">A second item</li>
                <li class="list-group-item">A third item</li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Header',
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;


    main{
        background-color: $color-green;
        border: 2px solid $color-white;
        border-radius: 20px;
    }
</style>