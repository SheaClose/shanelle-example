<template>
  <div class="home">
    <img src="../assets/logo.png">
    <HelloWorld />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '../components/HelloWorld.vue'

export default {
  components: {
    HelloWorld
  }
}
</script>
