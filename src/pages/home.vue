<template>
  <div class="home">{{ message }}</div>
</template>

<script>
export default {
  data() {
    return {
      message: "home"
    };
  }
};
</script>

<style lang="less" scoped>
.home {
  color: red;
}
</style>
