<template>
  <div>
    <el-button class="test">button {{ msg }}</el-button>
  </div>
</template>
<script>
export default {
  data() {
    return {
      msg: 'test'
    }
  }
}
</script>
