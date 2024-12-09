<template>
  <h1>Sign In</h1>
  <form action="">
    <div class="mb-3">
      <label for="nameInput" class="form-label">Name</label>
        <input type="text" class="form-control" id="nameInput" placeholder="João Albuquerque">
    </div>
    <div class="mb-3">
      <label for="emailInput" class="form-label">E-mail</label>
        <input type="email" class="form-control" id="emailInput" placeholder="name@example.com">
    </div>
    <div class="mb-3">
        <label for="passwordInput" class="form-label">Password</label>
        <input type="password" class="form-control" id="passwordInput1" placeholder="exemplo.: 102030">
    </div>
    <div class="mb-3">
        <label for="passwordConfirmationInput" class="form-label">Password Confirmation</label>
        <input type="password" class="form-control" id="passwordConfirmationInput1" placeholder="exemplo.: 102030">
    </div>

    <div class="d-grid gap-2">
      <button class="btn btn-primary" type="submit">Sign Up</button>
    </div>
  </form>
</template>
<script setup></script>
