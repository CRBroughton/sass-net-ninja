<template>
  <div class="lessons-banner">
    <img src="../assets/banner-2.png" />
    <div class="banner-content">
      <div class="wrapper">
        <span class="title">Our Lessons</span>
        <span class="sub-title">Are Easy</span>
        <ul>
          <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
          <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
          <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
        </ul>
      </div>
    </div>
  </div>
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
.lessons-banner {
  @include banner;
  li {
    text-transform: uppercase;
    font-size: 20px;
    max-width: 500px;
    margin: 60px 0;
  }
}
</style>