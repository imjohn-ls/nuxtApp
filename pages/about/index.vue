<template>
  <div>
    <el-button @click="toNews()">about</el-button>
    <el-button @click="toHome()">Home</el-button>
    <ul>
      <li>
        <nuxt-link :to="{ name: 'news', params: { id: '3306' } }"
          >Home</nuxt-link
        >
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },
  mounted() {},
  methods: {
    toNews() {
      this.$router.push({
        path: "/news"
      });
    },
    toHome() {
      this.$router.push({
        path: "/"
      });
    }
  }
};
</script>
<style lang="scss" scoped></style>
