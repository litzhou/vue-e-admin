<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>
<style>
.toolbar{
  padding: 10px;
  background: #f4f4f5;
  border-left:3px solid #409EFF;
}
.el-card__body{
  padding: 10px;
}
.el-card{
  margin-bottom: 5px; 
}
.el-submenu .el-menu-item {
    height: 40px;
    line-height: 40px;
}
.el-menu-item, .el-submenu__title {
    height: 40px;
    line-height: 40px;
}
.app-container{
  padding-top: 0px;
}
</style>

