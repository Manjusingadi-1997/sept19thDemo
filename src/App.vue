<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <h2>Vue.js Assignments</h2>
  <EventTrigger />
  <TwoWayBinding />
  <GetInputValue />
  <InputValuefromCheckRadio />
  <IfElseCondition />
  <ForLoop />
  <ParentComp />
  <ChildComp />
</template>

<script>

import EventTrigger from './components/EventTrigger.vue';
import TwoWayBinding from './components/TwoWayBinding.vue';
import GetInputValue from './components/GetInputValue.vue';
import InputValuefromCheckRadio from './components/InputValuefromCheckRadio.vue';
import IfElseCondition from './components/IfElseCondition.vue';
import ForLoop from './components/ForLoop.vue';
import ParentComp from './components/ParentComp.vue';
import ChildComp from './components/ChildComp.vue';

export default {
  name: 'App',
  components: {
    EventTrigger,
    TwoWayBinding,
    GetInputValue,
    InputValuefromCheckRadio,
    IfElseCondition,
    ForLoop,
    ParentComp,
    ChildComp
  }
}
</script>
<style scoped>
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 10%;
}

/* h2 {
  color: darkblue;
} */
</style>


