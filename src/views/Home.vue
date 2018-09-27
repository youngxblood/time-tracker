<template>
  <div class="home">
    <img alt="R6 logo" src="../assets/R6Logo.png" class="r6Logo">
    <LoginScreen msg="Please make sure you login!"/>
  </div>
</template>

<script>
// @ is an alias to /src
import LoginScreen from '@/components/LoginScreen.vue'

export default {
  name: 'home',
  components: {
    LoginScreen
  }
}

// R6 API TESTING 


</script>








<style>

.r6Logo {
  max-width: 450px;
  max-height: 200px;
}

</style>
