<template>
  <div>
    <div class="title">
      <span>豆瓣</span>
      <icon type="search" size="18" color="#00b600" />
      <button>打开豆瓣App</button>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="less">
.title {
  display: flex;

  align-items: center;
  height: 94rpx;
  border: 1rpx solid #eee;
  padding: 0 36rpx;
  span{
    font-size: 18px;
    color: #00b600
  }
  icon{
    flex:1;
    margin-left: 28rpx;
    margin-top: 8rpx;

  }
}
</style>