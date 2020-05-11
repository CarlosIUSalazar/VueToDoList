<template>
  <div>
    <h1>{{ name }}'s Task List</h1>
  </div>
</template>

<script>
export default {
  name: "AppTitle",
  props: ["name"]
};
</script>

<style>
h1 {
  text-align: center;
}
</style>
