
<template lang="pug">
  div.pj002
    div.main
      div.container
        TopMark 
        MenuMark 
        AlertBox 
        FooterLogoMark 
</template>

<script>
// @ is an alias to /src
import TopMark from "@/components/TopMark.vue";
import MenuMark from "@/components/MenuMark.vue";
import AlertBox from "@/components/AlertBox.vue";
import FooterLogoMark from "@/components/FooterLogoMark.vue";

export default {
  name: "Pj002",
  components: {
    TopMark,
    MenuMark,
    AlertBox,
    FooterLogoMark
  },
  methods: {}
};
</script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap");
.pj002 {
  height: calc(100vh - 64px);
}
.main {
  width: 100%;
  height: 100vh;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url("../assets/background.jpg");
  .container {
    height: auto;
    margin-bottom: 0px;
    height: 100vh;
    max-width: 100%;
    background: 0% 0% cover padding-box;
    background-color: rgba(0, 0, 0, 0.85);
  }
}
</style>
