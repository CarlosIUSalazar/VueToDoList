<template>
  <div class="task-list"></div>
</template>

<script>
/**
 * Requirements:
 * - The internal state of TaskList should has a property `keyName`,
 *   the value should be the property name in `data` that keep tracks of
 *   your list of Tasks
 * - The internal state of Tasks should be an array of object, which its element
 *   should contain `id`, `text`, and `isCompleted` properties.
 */
export default {
  name: "TaskList",
  data: () => ({
    keyName: "tasks",
    tasks: [
      { id: 1, text: "Learn JavaScript", isCompleted: false },
      { id: 2, text: "Learn Vue", isCompleted: false },
      { id: 3, text: "Build something awesome", isCompleted: false }
    ]
  })
};
</script>

<style>
.task-list {
  margin-left: 150px;
}
</style>
