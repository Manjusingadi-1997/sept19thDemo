<template>

    <!-- <h1 v-on:mousemove="getConsole()">Events</h1> -->
    <h2>On Click and Mouse events</h2>
    <button v-on:click="getData('Single click button pressed')" type="button">Click Here for 1 click alert</button>
    <br /><br />
    <button v-on:dblclick="getData('double click button pressed')" type="button">Click Here for 2 clicks</button>
    <br /><br />
    <button v-on:click="getCount()" type="button">Click Here to get count of single clicks</button>
    <h3>{{count}}</h3>
</template>

<script>
export default {
    name: "MyHome",
    data() {
        return {
            count: 0
        }
    },
    methods: {
        getData(data) {
            alert(data)
        },
        getConsole() {
            console.log("The mouse move event has been triggered");
        },
        getCount() {
            this.count = this.count + 1;
            console.log(this.count);
        }
    }

}
</script>

<style scoped>
h1 {
    color: orange;
}

button {
    background-color: aqua;
    color: crimson;
}

h2 {
    text-decoration: underline;
}
</style>
