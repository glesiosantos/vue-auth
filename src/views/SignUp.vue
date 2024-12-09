<template>
  <h1>Sign In</h1>
  <form @submit.prevent="handleSubmit">
    <div class="mb-3">
      <label for="firstNameInput" class="form-label">First Name</label>
        <input type="text" class="form-control" id="firstNameInput" v-model="form.first">
    </div>
    <div class="mb-3">
      <label for="lastNameInput" class="form-label">Last Name</label>
        <input type="text" class="form-control" id="lastNameInput" v-model="form.last">
    </div>
    <div class="mb-3">
      <label for="emailInput" class="form-label">E-mail</label>
        <input type="email" class="form-control" id="emailInput" v-model="form.email">
    </div>
    <div class="mb-3">
        <label for="passwordInput" class="form-label">Password</label>
        <input type="password" class="form-control" id="passwordInput1" v-model="form.password">
    </div>
    <div class="mb-3">
        <label for="passwordConfirmationInput" class="form-label">Password Confirmation</label>
        <input type="password" class="form-control" id="passwordConfirmationInput1" v-model="form.passwordConfirmation">
    </div>

    <div class="d-grid gap-2">
      <button class="btn btn-primary" type="submit">Sign Up</button>
    </div>
  </form>
</template>
<script setup>
import { ref } from 'vue';

  let form = ref({
    first: '',
    last: '',
    email: '',
    password: '',
    passwordConfirmation: ''
  })

  function handleSubmit () {
    console.log(form);
  }

</script>
