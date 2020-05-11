<template>
  <div>
    <app-title :name="name" />
    <task-list />
  </div>
</template>

<script>
import TaskList from "./components/TaskList";
import AppTitle from "./components/AppTitle";
export default {
  name: "App",
  data: () => ({
    name: "Your Name Here"
  }),
  components: {
    "app-title": AppTitle,
    "task-list": TaskList
  }
};
</script>
