<template>
  <div>
    <h1>header 2</h1>
    <p v-if="name">{{name}}</p>
	<p v-else>no name</p>
    <Header />
  </div>
</template>

<script>
import { defineComponent } from "@vue/composition-api";

export default defineComponent({
  setup() {
    const name = "";

    return { name };
  },
});
</script>

<style scoped>
h1 {
  color: red;
}
</style>
