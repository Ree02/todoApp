<template>
  <div>
    <Header />
    <AddTodo />
  </div>
</template>

<script lang="ts">
import Header from "~/components/Header.vue";
import AddTodo from "~/components/molecules/AddTodo.vue";
import { defineComponent } from "@vue/composition-api";

export default defineComponent({
  name: "IndexPage",
  components: { Header, AddTodo },
  setup() {
    return {};
  },
});
</script>

<style scoped>
div {
  background-color: #fffffe;
  font-size: 20px;
  color: #1b2d45;
}
</style>
