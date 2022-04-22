<template>
  <!-- <form style="padding: 20px">
    <sp-heading>
      {{ message }}
    </sp-heading>
    <img src="https://via.placeholder.com/150" class="logo" />
    <sp-body> Button has been clicked {{ count }} times. </sp-body>
    <sp-button v-on:click="increment">Click me</sp-button>
  </form> -->
  <div class="login-panel">
    <div class="logo-holder">
      <img
        src="https://via.placeholder.com/150"
        class="logo"
      />
    </div>
    <div class="no-acc-section">
      <p>Test!</p>
      <!-- <a href="google.com">Sign up</a> -->
    </div>
    <a href="google.com">Sign up</a>
    <!--  <div class="errors-holder">
      <div class="error-notification">
        <span class="error-text">An error occured!</span>
      </div>
    </div>
    <div class="login-form">
      <sp-textfield placeholder="Email adress" v-model="emailAdress">
        <sp-label isrequired="true" slot="label">Email adress</sp-label>
      </sp-textfield>
      <sp-textfield placeholder="Password" type="password" v-model="password">
        <sp-label isrequired="true" slot="label">Password</sp-label>
      </sp-textfield>
      <sp-button variant="cta" class="login-btn" @click="onLogin"
        >Login</sp-button
      >

      <sp-button variant="cta" class="login-btn" @click="toggleShowImage"
        >Show Image</sp-button
      >
    </div>
    <div class="no-acc-section">
      <p>Don't have an account?</p>
      <a href="google.com">Sign up</a>
    </div> -->
  </div>
</template>
<script>
import { ref, defineComponent } from "vue";

export default {
};
</script>
<style>
</style>