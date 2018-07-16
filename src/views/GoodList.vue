<template>
  <div class="list">
    {{ data }}
  </div>
</template>

<script>
  export default {
    data () {
      return {
        data: 'goodList'
      }
    }
  }
</script>

<style lang="less" scoped>
.list {
  background-color: #f5f7fc;
}
</style>
