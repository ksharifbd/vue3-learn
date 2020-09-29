<template>
  <Card showFooter>
    <template v-slot:cardHeader> This is card header </template>
    <template v-slot:cardBody> This is card Body </template>
    <template v-slot:cardFooter>
      <button name="random" v-on:click="handleClick">Click me</button>
    </template>
  </Card>
</template>

<script>
import Card from "../Card/Card";

export default {
  components: {
    Card,
  },
  methods: {
    handleClick: (e) => console.log(e.target),
  },
};
</script>