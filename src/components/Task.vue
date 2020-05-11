<template>
  <div>
    <button>{{ isCompleted ? "REVERT" : "COMPLETE" }}</button>
    <span v-bind:class="{ complete: isCompleted }">{{ text }}</span>
  </div>
</template>

<script>
export default {
  name: "Task",
  props: ["text", "isCompleted"]
};
</script>

<style>
.complete {
  text-decoration: line-through;
}
</style>
