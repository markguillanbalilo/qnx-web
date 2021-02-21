<template>
  <div id="reg-page">
    <div class="container">
      <div class="page-content">
        <h2 class="text-center">Join us!</h2>
        <div class="row">
          <div class="col-md-5">
            <img
              src="https://s3-ap-southeast-1.amazonaws.com/kalibrr-company-assets/images/68TXVU3NP9FCWJGSA3QX-5892d4d6.jpg"
              class="company-photo"
            />
          </div>
            <div class="col-md-5">
              <div class="form-group">
                <form>
                  <label>Full Name: </label><br />
                  <input
                    type="text"
                    name="first-name"
                    placeholder="Full Name"
                    required
                  /><br />
                  <label>Gender: </label>
                  <input type="radio" name="gender" label="Male" value="male" />
                  <label for="male">Male</label>
                  <input
                    type="radio"
                    name="gender"
                    label="Female"
                    value="female"
                  />
                  <label for="male">Female</label><br />
                  <label>Birth Date: </label><br />
                  <input type="date" name="birthdate" /><br />
                  <label>Email Address: </label><br />
                  <input
                    type="email"
                    name="email"
                    label="Email: "
                    placeholder="Email Address"
                    required
                  />
                  <input type="checkbox" name="newsletter" checked />
                  <label for="newsletter">Send me newsletters</label><br />
                  <label>Mobile Number: </label><br />
                  <input type="number" name="contact-number" /><br />
                  <label>Education: </label><br />
                  <select class="education">
                    <option>High School Diploma</option>
                    <option>College Undergraduate</option>
                    <option selected>Bachelor's Degree</option>
                  </select>
                  <br />
                  <label>Username: </label><br />
                  <input
                    type="text"
                    name="username"
                    placeholder="username"
                    required
                  /><br />
                  <label>Password: </label><br />
                  <input
                    type="password"
                    name="password"
                    id="password"
                    placeholder="password"
                    required
                  /><br />
                  <input
                    type="password"
                    name="verify-password"
                    id="verify-password"
                    placeholder="verify password"
                    required
                  /><br />
                  <input type="submit" />
                </form>
              </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.company-photo {
  width: 100%;
  box-shadow: 10px 10px 10px;
  margin: 5px;
}
</style>


