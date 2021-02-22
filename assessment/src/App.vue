<template>
  <div id="app">
    <nav class="navbar" id="navigation">
      <a href=""
        ><img
          src="https://questronix.com.ph/wp-content/uploads/2019/03/logoflyer.png"
          class="logo"
      /></a>
      <div class="nav">
        <a @click="$router.push('/')" class="nav-item">Home</a>
        <a @click="$router.push('/blogposts')" class="nav-item"> Blogs </a>
        <a @click="$router.push('/loginhere')" class="nav-item"> Log In </a>
        <a @click="$router.push('/registerhere')" class="nav-item">
          Register
        </a>
      </div>
    </nav>
    <footer>
      <div row>
        <div col-md-4>
          </div>
        <div col-md-4>
          <p>&#169; Questronix Corporation</p>
          </div>
        <div col-md-4>
          </div>

        </div> 

    </footer>

    <router-view />
  </div>
</template>

<style scoped>
.logo {
  width: 15%;
}

.navbar {
  background-color: rgb(236, 236, 236);
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 9999;
  width: 100%;
}

.nav-item {
  float: right;
  text-align: center;
  padding: 10px;
  text-decoration: none;
}

.nav-item:hover {
  cursor:pointer;
  color:rgb(9, 9, 82);
  border-bottom: 1px solid rgb(9, 9, 82);
}

.nav-item:visited {
  border-bottom: 1px solid rgb(9, 9, 82);

}

</style>
