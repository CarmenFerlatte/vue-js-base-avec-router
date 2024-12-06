<template>
    <div id="app">
        <img alt="Vue logo" src="./assets/images/logo.png">
        <h1>{{ message }}</h1>
        <router-view></router-view>
    </div>
</template>

<script>
export default {
    data() {
        return {
            message: 'Salut le monde !'
        }
    }
}
</script>

<style scoped>

</style>