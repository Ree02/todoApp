<template>
  <div>
    <input
      type="text"
      v-model="inputTitle"
      placeholder="タスク名を追加してください"
    />
  </div>
</template>

<script>
import { defineComponent } from "@vue/composition-api";

export default defineComponent({
  setup() {},
});
</script>

<style scoped>
input {
  border: 2px solid #444444;
  border-radius: 5px;
  background: #ffff;
  width: 400px;
  height: 35px;
  font-size: 15px;
}
</style>
