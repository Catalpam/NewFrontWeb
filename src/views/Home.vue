<template>
  <ebutton />
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <HelloWorld msg="Welcome to My Site" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import ebutton from "@/components/button.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    ebutton,
  },
  methods: {
    prin() {
      this.$console.log("gdfgdsfgdfsgdfshjggjhdfs")
    }
  },
};
</script>
