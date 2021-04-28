<template>
   <div>
     <p>news content</p>
     <p>{{$route.params.id}}</p>
   </div>
</template>
<script>
export default {
  validate({params}) {
    return /^\d+$/.test(params.id)
  },
  data() {
    return {};
  },
  mounted() {},
  methods: {}
};
</script>
<style lang='scss' scoped></style>
