<template>
  <div id="reg-page">
    <div class="page-title">
        <h2 class="text-center title">Join us!</h2>
      </div>
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <img
            src="https://s3-ap-southeast-1.amazonaws.com/kalibrr-company-assets/images/68TXVU3NP9FCWJGSA3QX-5892d4d6.jpg"
            class="company-photo"
          />
        </div>
        <div class="col-md-5 reg-form">
          <div class="form-group">
            <form>
              <label>Full Name: </label>
              <input
                type="text"
                name="first-name"
                placeholder="Full Name"
                class="form-control"
                required
              />
              <label>Gender: </label><br />
              <div class="form-check form-check-inline">
                <input
                  type="radio"
                  id="male"
                  value="male"
                  class="form-check-input"
                />
                <label class="form-check-label" for="male">Male</label>
              </div>
              <div class="form-check form-check-inline">
                <input
                  type="radio"
                  name="gender"
                  id="female"
                  value="female"
                  class="form-check-input"
                />
                <label class="form-check-label" for id="female">Female</label>
              </div>
              <br />
              <label>Birth Date: </label><br />
              <input type="date" name="birthdate" class="form-control" />
              <label>Email Address: </label>
              <input
                type="email"
                name="email"
                label="Email: "
                placeholder="Email Address"
                class="form-control"
                required
              />
              <div class="form-check form-check-inline">
                <input
                  type="checkbox"
                  id="newsletter"
                  checked
                  class="form-check-input"
                />
                <label for="newsletter" class="form-check-label"
                  >Send me newsletters</label
                >
              </div>
              <br />
              <label>Mobile Number: </label>
              <input type="number" name="contact-number" class="form-control" required />
              <label>Education: </label>
              <div class="form-group">
                <select class="education">
                  <option>High School Diploma</option>
                  <option>College Undergraduate</option>
                  <option selected>Bachelor's Degree</option>
                </select>
              </div>
              <label>Username: </label>
              <input
                type="text"
                name="username"
                placeholder="username"
                class="form-control"
              />
              <label>Password: </label>
              <input
                type="password"
                name="password"
                id="password"
                placeholder="password"
                class="form-control"
                required
              />
              <input
                type="password"
                name="verify-password"
                id="verify-password"
                placeholder="verify password"
                class="form-control"
                required
              />
              <span id="warning"></span>
            </form>
            <input type="submit" class="btn btn-primary" v-on:click="greet" />
          </div>
        </div>
      </div>
    </div>
    </div>   
</template>

<script>
export default {
  el: "#reg-page",
  methods: {
    greet: function () {
      if (
        document.getElementById("password").value !=
        document.getElementById("verify-password").value
      ) {
        document.getElementById("warning").innerHTML =
          "Password does not match!";
      } else {
        document.getElementById("warning").innerHTML = "Password match!";
      }
    },
  },
};
</script>

<style scoped>
input::-webkit-outer-spin-button,
input::-webkit-inner-spin-button {
  -webkit-appearance: none;
}

.company-photo {
  width: 100%;
  box-shadow: 10px 10px 10px;
  margin-top: 130px;
  vertical-align: middle;
}

.reg-form {
  margin-left: 30px;
  margin-top:50px;
}

input[type="submit"] {
  margin-top: 20px;
}

.page-title {
  margin-top: 50px;
  background-color: rgb(9, 9, 66);
  color:azure;
  height: 100px;

}

.title {
  line-height: 100px;
  
}

@media screen and (max-width:800px) {
  .page-title {
    margin-top: 50px;
    height: 90px;
  }

  .title {
    font-size: 150%;
    line-height: 90px;
  }

  .company-photo {
    margin-top: 40px;
  }

  form, input {
    font-size: 80%;
  }

  form {
    margin-left: 0;
  }
  
}


</style>


