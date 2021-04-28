<template>
   <div>
    <p>{{$route.params.id}}</p>
     <nuxt-link to="news/456">news 456</nuxt-link>
     <nuxt-link to="news/123">news 123</nuxt-link>
     <nuxt-link to="news/test">news test</nuxt-link>
     </div>
</template>
<script>
export default {
  data() {
    return {};
  },
  mounted() {
    console.log(this.$route.params);
  },
  methods: {}
};
</script>
<style lang='scss' scoped></style>
