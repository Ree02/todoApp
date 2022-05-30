<template>
  <div>
    <Header />
    <Tutorial />
  </div>
</template>

<script lang="ts">
import Header from "~/components/Header.vue";
import { defineComponent } from "@vue/composition-api";

export default defineComponent({
  name: "IndexPage",
  components: { Header },
  setup() {
    return {};
  },
});
</script>

<style scoped>
div {
  background-color: #fffffe;
}
</style>

function defineComponent(arg0: { name: string; components: { Header: any; };
setup(): void; }) { throw new Error("Function not implemented."); }
