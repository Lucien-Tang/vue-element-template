<template>
  <div class="shopsManager-container">
    <div class="shopsManager-text">
      这里是商铺管理 
      <el-button type="primary" @click="$router.push({name: 'newShops'})">新建商铺</el-button>
    </div>
  </div>
</template>

<script>

export default {
  name: 'shopsManager',
  mounted() {}
}
</script>

<style lang="scss" scoped>
.shopsManager {
  &-text {
    font-size: 30px;
    line-height: 46px;
  }
}
</style>
