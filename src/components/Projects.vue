<template>
  <section id="projects">
    <div class="wrapper">
      <h1>Our Projects</h1>
      <ul>
        <li><img src="https://via.placeholder.com/150" /></li>
        <li><img src="https://via.placeholder.com/150" /></li>
        <li><img src="https://via.placeholder.com/150" /></li>
        <li><img src="https://via.placeholder.com/150" /></li>
        <li><img src="https://via.placeholder.com/150" /></li>
        <li><img src="https://via.placeholder.com/150" /></li>
        <li><img src="https://via.placeholder.com/150" /></li>
        <li><img src="https://via.placeholder.com/150" /></li>
        <li><img src="https://via.placeholder.com/150" /></li>
        <li><img src="https://via.placeholder.com/150" /></li>
        <li><img src="https://via.placeholder.com/150" /></li>
        <li><img src="https://via.placeholder.com/150" /></li>
      </ul>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  setup() {
    return {};
  },
});
</script>

<style scoped lang="scss">
#projects li {
  @include grid(2, 2%);
  img {
    width: 100%;
  }
}
</style>