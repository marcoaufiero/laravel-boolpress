<template>
    <div id="loader">
        <div class="spinner-border text-primary" role="status">
            <span class="visually-hidden">Loading...</span>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Loader'
    }
</script>

<style lang="scss" scoped>
    #loader{
        position: fixed;
        z-index: 3;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: rgba(0,0,0,0.8);
    }
</style>