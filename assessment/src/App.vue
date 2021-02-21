<template>
  <div id="app">
    <nav class="navbar">
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

    <router-view />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.logo {
  width: 15%;
}

.navbar {
  background-color: rgb(197, 197, 255);
}

.nav-item {
  float: right;
  text-align: center;
  padding:10px;

}

.nav-item:hover {
  
}
</style>
