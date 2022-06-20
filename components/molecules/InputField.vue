<template>
  <div class="container">
    <InputText />
    <Button @btn-click="addTodo" />
  </div>
</template>

<script>
import { defineComponent } from "@vue/composition-api";
import Button from "@/components/atoms/Button.vue";
import InputText from "../atoms/InputText.vue";

export default defineComponent({
  components: {
    Button,
    InputText,
  },
  setup() {
    const inputTitle = "";
    const addTodo = () => {
      console.log("aaa");
      console.log("げっと: " + inputTitle);
      this.$emit("newTodoTitle");
    };
    return { inputTitle, addTodo };
  },
});
</script>

<style scoped>
.container {
  margin-top: 20px; /* ヘッダーとの間の隙間 */
  width: 100%;
  display: flex; /* input部分とbutton部分を横並びにする */
  justify-content: center; /* input部分とbutton部分を中央揃えにする */
}
</style>
