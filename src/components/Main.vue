<template>
    <div class="main container d-flex justify-content-between border">
        <div v-for= "n in 3" :key="index" class="card border-5" style="width: 18rem;">
            <ul class="list-group list-group-flush">
                <a href="#" class=""><li class="list-group-item rounded-5">An item</li></a>
                <a href="#"><li class="list-group-item rounded-5">A second item</li></a>
                <a href="#"><li class="list-group-item rounded-5">A third item</li></a>
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
        //border-radius: 50px;
    }
</style>