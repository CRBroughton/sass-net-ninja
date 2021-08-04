<template>
  <header>
    <nav id="main-nav">
      <div class="wrapper">
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About Us</a></li>
          <li><a href="#">Lessons</a></li>
          <li><a href="#">Portfolio</a></li>
          <li><a href="#">Blog</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </div>
    </nav>
    <div class="lead-banner">
      <img src="../assets/banner-1.png" />
      <div class="banner-content">
        <div class="wrapper">
          <span class="title">Check our video</span>
          <span class="sub-title">Learning in 6 weeks</span>
        </div>
      </div>
    </div>
  </header>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  setup() {
    return {};
  },
});
</script>

<style scoped>
</style>