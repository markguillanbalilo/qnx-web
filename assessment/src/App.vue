<template>
  
  <div id="app">
    <nav class="navbar navbar-light ">
      <a href=""
        ><img
          src="https://questronix.com.ph/wp-content/uploads/2019/03/logoflyer.png"
          class="logo"
      /></a>
      <a @click="$router.push('/')" class="nav-item">Home</a>
      <a @click="$router.push('/blogposts')" class="nav-item">
        Blogs
      </a> 
      <a @click="$router.push('/loginhere')" class="nav-item">
        Log In
      </a>
      <a @click="$router.push('/registerhere')" class="nav-item">
        Register
      </a>
      
      


    </nav>

    <router-view />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>

.logo {
  width:20%;
}

.navbar {
  background-color: rgb(197, 197, 255);
}

.nav-item {
  float:right;
}
</style>
