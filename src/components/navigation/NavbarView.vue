<template>
  <ul>
    <List list="Home" />
    <List list="About Us" />
    <List list="Service" />
    <List list="Contact Us" />
  </ul>
</template>

<script>
import List from "./ListView.vue";
export default {
  components: {
    List,
  },
};
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
ul {
  display: flex;
  list-style: none;
  background-color: #9c27b0;
}
</style>
