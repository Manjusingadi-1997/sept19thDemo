<template>
    <h2>Getting the value from input field</h2>
    <input type="text" placeholder="Enter the email ID" v-model="email" /><br />
    <input type="password" placeholder="Enter the password" v-model="password" />
    <br /><br />
    <button v-on:click="getData()" type="button">Get Values</button>


</template>

<script>
export default {
    name: 'GetInputValue',
    data() {
        return {
            email: null,
            password: null,
        }
    },
    methods: {
        getData() {
            console.log("Email ID is :", this.email);
            console.log("Password is :", this.password);

        }
    }

}
</script>
<style scoped>
h2 {
    color: black;
    text-decoration: underline;
}
</style>
