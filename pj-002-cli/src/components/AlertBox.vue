<template lang="pug">
  .alert(@click="alert()")
    v-btn.button(outlined color="white" tile height='80px' width='278px') continue
      span.button-mark
        font-awesome-icon(icon="chevron-right")
</template>
<script>
export default {
  data: function() {
    return {
      message: "コンティニューボタンが押されました",
    };
  },
  methods: {
    alert: function() {
      window.alert(this.message);
    },
  },
};
</script>

<style scoped lang="scss">
.button {
  color: #ffffff;
  font-size: 20px;
  border: 1px solid #ffffff;
  padding-top: 40px;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  margin: 350px auto;
  position: absolute;
  text-align: center;
  font-family: "Bebas Neue", cursive;
  letter-spacing: 1.6px;

  .button-mark {
    color: #ffffff;
    float: right;
    padding-left: 40px;
  }
}
</style>
