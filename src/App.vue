<template>
  <TheHeader />
  <Services />
  <Lessons />
  <Projects />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import TheHeader from "@/components/TheHeader.vue";
import Services from "@/components/Services.vue";
import Lessons from "@/components/Lessons.vue";
import Projects from "@/components/Projects.vue";

export default defineComponent({
  components: {
    TheHeader,
    Services,
    Lessons,
    Projects,
  },
  setup() {
    return {};
  },
});
</script>

<style scoped>
body {
  font-family: arial;
  background: #f8f9fb;
}

html,
body,
ul,
ol,
li,
form,
fieldset,
legend {
  margin: 0;
  padding: 0;
}

h1,
h2,
h3,
h4,
h5,
h6,
p {
  margin-top: 0;
}

fieldset,
img {
  border: 0;
}

li {
  list-style: none;
}

.wrapper {
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
  box-sizing: border-box;
}
</style>