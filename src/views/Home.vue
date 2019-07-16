<template>
  <div class="home">
    <div class="title">测测你的安全意识有多强</div>
    <div class="tips">你的人生稳如泰山还是危机四伏</div>
  </div>
</template>

<script>
export default {
  name: "home"
};
</script>

<style lang="scss" scoped>
.home {
  max-width: 750px;
  width: 100%;
  font-size: 0.24rem;
  text-align: center;

  .title {
    @extend .MARGIN_TOP_20;
    font-size: 0.4rem;
  }

  .tips {
    @extend .MARGIN_TOP_20;
    color: $c_66;
  }
}
</style>
