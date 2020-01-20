<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="#e93b3d">
      <img slot="item-icon" src="../../assets/img/tabbar/category.png" alt="">
      <img slot="item-icon-active" src="../../assets/img/tabbar/category-active.png" alt="">
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category" activeColor="#e93b3d">
      <img slot="item-icon" src="../../assets/img/tabbar/category.png" alt="">
      <img slot="item-icon-active" src="../../assets/img/tabbar/category-active.png" alt="">
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart" activeColor="#e93b3d">
      <img slot="item-icon" src="../../assets/img/tabbar/category.png" alt="">
      <img slot="item-icon-active" src="../../assets/img/tabbar/category-active.png" alt="">
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile" activeColor="#e93b3d">
      <img slot="item-icon" src="../../assets/img/tabbar/category.png" alt="">
      <img slot="item-icon-active" src="../../assets/img/tabbar/category-active.png" alt="">
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>
<script>
  import TabBar from '../tabbar/TabBar'
  import TabBarItem from '../tabbar/TabBarItem'
  export default {
    name: "MainTabBar",
    components: {
      TabBar,
      TabBarItem
    }
  };
</script>
<style>
</style>
