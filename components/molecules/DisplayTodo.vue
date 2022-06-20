<template>
  <div class="lists">
    <ul>
      <li>task1</li>
      <li>task2</li>
      <li>task3</li>
    </ul>
  </div>
</template>

<script>
import { defineComponent } from "@vue/composition-api";

export default defineComponent({
  setup() {},
});
</script>

<style scoped>
.lists {
  margin: auto;
  margin-top: 70px;
  border-collapse: collapse;
}
li {
  list-style: none;
}
</style>
