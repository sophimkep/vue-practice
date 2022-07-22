<template>
  <li>
    {{ list }}
  </li>
</template>

<script>
export default {
  props: {
    list: String,
  },
};
</script>

<style>
li {
  padding: 1rem;
  font-size: 15px;
  color: #fff;
}
</style>
