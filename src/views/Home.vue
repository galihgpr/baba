<template>
  <div class="home">
    <navbar />
    <jumbotron />
  </div>
</template>

<script>
// @ is an alias to /src
import navbar from "@/components/navbar.vue";
import jumbotron from "@/components/jumbotron";
export default {
  name: "Home",
  components: {
    navbar,
    jumbotron
  }
};
</script>
<style>
.home {
  height: 100%;
}
</style>
