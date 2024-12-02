<template>
  <headerE/>
  <UserStorage/>
  <FooterObject/>
</template>

<script>
import HeaderE from './components/HeaderE.vue';
import UserStorage from "@/components/UserStorage.vue";
import FooterObject from "@/components/FooterObject.vue";

export default {
  name: 'App',
  components: {
    HeaderE, UserStorage, FooterObject
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
