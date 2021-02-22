<template>
  <div id="landing-page">
    <div>
      <img
        src="https://questronix.com.ph/wp-content/uploads/2019/06/lenovo.png"
        alt="questronix-poster"
        class="poster"
      />

      <div class="col-md-12 welcome">
        <h1 class="text-center title-slide">Welcome to Questronix!</h1>
      </div>

      <div class="d-flex justify-content-center overview">
        <div class="overview-text">
          <h2 class="text-center">
            We make <i>Digital Transformation</i> possible.
          </h2>
          <p class="text-center">
            Your trusted business partner for IT solutions and services.<br />Questronix
            has grown to be one of the largest IT solutions and service
            providers and systems integrators in the Philippines since 1987<br />
            that has earned awards and certificates through its focused
            professional team of experts.
          </p>
        </div>
      </div>

      <div class="row core-values">
        <div class="col-4 col-md-2 text-center">
          <License />
          <p class="caption">Leadership</p>
        </div>
        <div class="col-4 col-md-2 text-center">
          <Church />
          <p class="caption">Faith</p>
        </div>
        <div class="col-4 col-md-2 text-center">
          <Lock />
          <p class="caption">Integrity</p>
        </div>
        <div class="col-4 col-md-2 text-center">
          <TrophyAward />
          <p class="caption">Excellence</p>
        </div>
        <div class="col-4 col-md-2 text-center">
          <AccountGroup />
          <p class="caption">Teamwork</p>
        </div>
        <div class="col-4 col-md-2 text-center">
          <Handshake />
          <p class="caption">Client First</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Church from "vue-material-design-icons/Church.vue";
import AccountGroup from "vue-material-design-icons/AccountGroup.vue";
import TrophyAward from "vue-material-design-icons/TrophyAward.vue";
import Lock from "vue-material-design-icons/Lock.vue";
import Handshake from "vue-material-design-icons/Handshake.vue";
import License from "vue-material-design-icons/License.vue";

export default {
  name: "landing-page",
  components: {
    Church,
    AccountGroup,
    TrophyAward,
    Lock,
    Handshake,
    License,
  },
};
</script>

<style scoped>
#landing-page {
  overflow: hidden;
  box-sizing: border-box;
  width: 100%;
}
.welcome {
  background-color: rgb(9, 9, 66);
  height: 170px;
}

h1 {
  font-size: 400%;
  color: azure;
  line-height: 170px;
}
.poster {
  width: 100%;
  margin-top: 50px;
}

.overview {
  width: 100%;
  height: 300px;
  background-image: url(https://images.pexels.com/photos/574070/pexels-photo-574070.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940);
  background-attachment: fixed;
  color: white;
}

.overview-text {
  margin: 6%;
}

.core-values {
  height: 100%;
}
.material-design-icon {
  font-size: 500%;
  margin-top: 20px;
  margin-bottom: 20px;
}

@keyframes slide-title {
  0% {
    transform: translateY(-60%);
    opacity: 0.01;
  }
  100% {
    transform: translateY(0%);
    opacity: 1;
  }
}

.title-slide {
  /* This section calls the slideInFromLeft animation we defined above */
  animation: 1s ease-out slide-title;
}

@media screen and (max-width:800px) {

  .poster {
    margin-top: 50px;
  }
  .title-slide {
    font-size: 200%;
  }

  .overview-text {
    font-size: 90%;
  }

  h2 {
    font-size: 150%;
  }

  .material-design-icon {
    font-size: 250%;
  }

  .caption {
    font-size: 90%;
  }
  
}

</style>

