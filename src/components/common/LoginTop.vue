<template>
  <div class="LoginTop">
    <div>{{ middleTop }}</div>
  </div>
</template>

<script>
export default {
  props: ["middleTop"]
};
</script>

<style lang="scss">
.LoginTop {
  height: 12.5vw;
  background: white;
  display: flex;
  div {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 4.4444vw;
  }
}
</style>
