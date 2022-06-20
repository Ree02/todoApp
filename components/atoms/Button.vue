<template>
  <div>
    <button class="add-button" type="button" @click="onClick">追加</button>
  </div>
</template>

<script>
import { defineComponent } from "@vue/composition-api";

export default defineComponent({
  setup() {
    const onClick = () => {
      this.$emit("on-click");
      console.log("click");
    };
    return {
      onClick,
    };
  },
});
</script>

<style scoped>
.add-button {
  border: 2px solid #1b2d45;
  border-radius: 5px;
  background: #1b2d45;
  color: #fffffe;
  width: 120px;
  height: 40px;
  font-size: 15px;
  margin-left: 5px;
}
</style>
