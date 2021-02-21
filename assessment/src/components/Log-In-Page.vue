<template>
  <div id="log-in-page">
    <div class="log-in">
      <div class="col-1">
        <label>Username:</label>
        <br />
        <label>Password:</label>
      </div>
      <div class="col-2" id="log-in">
        <form class="login-form">
          <input
            type="text"
            name="username"
            placeholder="Enter username"
            class="field"
            id="password"
          /><br />
          <input
            type="password"
            name="password"
            placeholder="Enter password"
            class="field"
            id="verify-password"
          /><br />
        </form>
      </div>
      <input type="submit" v-on:click="verify" /><br />
      <p>
        Not a member yet?
        <button @click="$router.push('/registerhere')" class="sign-up">
          Sign-up Here
        </button>
      </p>
    </div>
  </div>
</template>

<script>

</script>


