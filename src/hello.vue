<template>
  <loginPage></loginPage>
  <!-- <form style="padding: 20px">
    <sp-heading>
      {{ message }}
    </sp-heading>
    <img src="https://via.placeholder.com/150" class="logo" />
    <sp-body> Button has been clicked {{ count }} times. </sp-body>
    <sp-button v-on:click="increment">Click me</sp-button>
  </form> -->
</template>

<script>
import { ref } from "vue";
import loginPage from "./login-page.vue";

export default {
  components: {
    loginPage,
  },
  setup() {
    let count = ref(0);
    const message = "Hello World Vue 3 Component!";

    const increment = () => {
      count.value++;
    };
    return { count, message, increment };
  },
};
</script>
