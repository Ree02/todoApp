<template>
  <div>
    <div>
      <inputField @newTodoTitle="newTodo" />
    </div>
    <div>
      <DisplayTodo />
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "@vue/composition-api";
import InputField from "~/components/molecules/InputField.vue";
import DisplayTodo from "../molecules/DisplayTodo.vue";

export default defineComponent({
  components: {
    InputField,
    DisplayTodo,
  },
  setup() {},
});
</script>

<style scoped></style>
