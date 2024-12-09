<template>
  <h1>Sign In</h1>
  <form action="">
    <div class="mb-3">
      <label for="emailInput" class="form-label">Email address</label>
        <input type="text" class="form-control" id="emailInput">
    </div>
    <div class="mb-3">
        <label for="passwordInput" class="form-label">Password</label>
        <input type="password" class="form-control" id="passwordInput">
    </div>

    <div class="d-grid gap-2">
      <button class="btn btn-primary" type="submit">Sign In</button>
    </div>
  </form>
</template>
<script setup></script>
