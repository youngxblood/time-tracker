<template>
    <div class="home">
        <h1>{{ msg }}</h1>
    </div>
</template>

<script>
export default {
  name: 'LoginScreen',
  props: {
    msg: String
  }
}
</script>