<template>
  <div class="container">
    <InputField />
    <Button />
  </div>
</template>

<script>
import { defineComponent } from "@vue/composition-api";
import InputField from "../atoms/InputField.vue";
import Button from "../atoms/Button.vue";

export default defineComponent({
  components: {
    InputField,
    Button,
  },
  setup() {},
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
