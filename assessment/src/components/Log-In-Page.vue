<template>
  <div id="log-in-page">
    <div class="row log-in">
      <div class="col-md-4"></div>
      <div class="col-md-4">
        <div class="form-group">
          <form>
            <label>Username:</label>
            <input
              type="text"
              name="username"
              placeholder="Enter username"
              class="form-control"
              id="username"
            />
            <label>Password:</label>
            <input
              type="password"
              name="password"
              placeholder="Enter password"
              class="form-control"
              id="password"
            />
            <br />
            <input
              type="submit"
              v-on:click="verify"
              class="btn btn-primary"
            /><br />
            <p class="member">
              Not a member yet?
              <button @click="$router.push('/registerhere')" class="sign-up">
                Sign-up Here
              </button>
            </p>
          </form>
        </div>
      </div>
      <div class="col-md-4"></div>
    </div>
  </div>
</template>


<style scoped>
.log-in {
  margin: 10%;
}

form {
  border: 2px solid black;
  padding: 20px;
  border-radius: 10px;
}

@media screen and (max-width: 800px) {
  form {
    margin-top: 100px;
    width: 100%;
  }
  label {
    font-size: 80%;
  }

  input {
    font-size: 80%;
  }

  p,
  button {
    font-size: 90%;
  }
}
</style>


