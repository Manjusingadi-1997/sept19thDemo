<!-- Two way binding is binding the view with the model that is if something changes in view should automatically reflect in model and vice versa . V-model directive is being used here-->

<template>

    <h2>Two Way Binding</h2>
    <input type="text" v-model="count" />
    <h3>{{count}}</h3>


</template>
  
<script>
export default {
    name: 'TwoWayBinding',
    data() {
        return {
            count: 0
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