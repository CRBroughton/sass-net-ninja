<template>
  <section id="services">
    <div class="wrapper">
      <h1>Services</h1>
      <p></p>
      <ul>
        <li>
          <img src="../assets/icon-1.png" />
          <a href="#">Recording<br />services</a>
        </li>
        <li>
          <img src="../assets/icon-2.png" />
          <a href="#">Get a printed<br />certificate</a>
        </li>
        <li>
          <img src="../assets/icon-3.png" />
          <a href="#">Lessons via<br />Skype</a>
        </li>
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
#services {
  margin-bottom: 60px;
  li {
    float: left;
    box-sizing: border-box;
    text-align: center;
    width: (100% / 3);
  }
  img {
    width: 60%;
    margin: 20px 20%;
  }
  a {
    text-decoration: none;
    color: $deepBlue;
    font-weight: bold;
    &:hover {
      color: complement($deepBlue);
    }
  }
  ul {
    @include clearFix;
  }
}
</style>