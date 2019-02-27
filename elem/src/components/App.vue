<template>
  <div>
    <div class="tab boreder-1px">
      <div class="tab-item">
        <route-link to="/goods">商品</route-link>
      </div>
      <div class="tab-item">
        <route-link to="/goods">评论</route-link>
      </div>
      <div class="tab-item">
        <route-link to="/goods">商家</route-link>
      </div>
      <keep-alive>
        <router-view :seller="seller"></router-view>
      </keep-alive>
    </div>
  </div>
</template>

<script>

    export default {
        name: ''
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">


</style>
