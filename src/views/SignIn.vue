<script setup></script>

<template>
  <div class="content">
    <h1>Sign in</h1>
    <p class="center-text">
      <RouterLink to="/signup">Need an account?</RouterLink>
    </p>
    <div class="form-content">
      <form>
        <div class="form-field">
          <input type="text" placeholder="Email" />
        </div>
        <div class="form-field">
          <input type="password" placeholder="Password" />
        </div>
        <div class="form-field"><button type="submit">Sign in</button></div>
      </form>
    </div>
  </div>
</template>

<style>
.content {
  width: 1280px;
  margin: 0 auto;
  text-align: center;
}
.center-text a {
  color: #5cb85c;
}
/* .content form {
  display: inline-grid;
  width: 50%;
} */
.content form input {
  margin: 10px 0;
  padding: 10px 15px;
  border-radius: 5px;
  border-color: rgba(0, 0, 0, 0.1);
  font-size: 1.25rem;
  width: 100%;
}
.form-field{width: 50%;margin: 0 auto;}
.form-field:nth-child(3){text-align: right;}
.form-field button{padding: 15px 25px;background-color: #5cb85c;color: white;font-size: 20px;border: transparent;border-radius: 4px;}
</style>
