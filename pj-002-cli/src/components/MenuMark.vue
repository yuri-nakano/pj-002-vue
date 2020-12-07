<template lang="pug">
  div.menu
    v-btn(color='white' fab width= '70px' height='70px' dark icon)
      font-awesome-icon.fa-bars(icon="bars" size="3x")
</template>

<style scoped lang="scss">
.menu {
  width: 78px;
  height: 78px;
  float: right;
  margin-top: 44px;
  background-color: white;
  border-radius: 50%;
  margin-right: 36px;
}

.fa-bars {
  color: #4492cb;
  margin-top: 5px;
  margin-left: 7px;
}
</style>
