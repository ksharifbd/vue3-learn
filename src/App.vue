<template>
  <Card showFooter>
    <template v-slot:cardHeader> This is card header </template>
    <template v-slot:cardBody> This is card Body </template>
    <template v-slot:cardFooter>This is card footer </template>
  </Card>
</template>

<script>
import Card from "./components/Card/Card";

export default {
  name: "App",
  components: {
    Card,
  },
};
</script>
