<template>
    <h2>{{message}}</h2>
    <button v-on:click="sendData()">Call function</button>
</template>

<script>
export default {
    name: 'ChildComp',
    props: {
        message: String,
        sendData: Function
    }

}
</script>

<style>

</style>
