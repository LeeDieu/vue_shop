<template>
  <el-button type="info" @click="quit">退出</el-button>
</template>

<script>
export default {
  methods: {
    quit() {
      window.sessionStorage.clear();
      this.$router.push("/login");
    },
  },
};
</script>

<style lang="less" scoped>
</style>>

