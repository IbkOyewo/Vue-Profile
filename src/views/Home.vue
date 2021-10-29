<template>
  <div class="home">
    <img alt="logo" src="/assets/Screenshot_2021-10-29_at_01.38.22-removebg-preview.png" />
    <Welcome/>
    
  </div>
</template>

<script>
// @ is an alias to /src
import Welcome from "@/components/Welcome.vue";

export default {
  name: "Home",
  components: {
    Welcome
  },
};
</script>

<style scoped>
img{
  width: 200px;
  height: 180px;
}
</style>
