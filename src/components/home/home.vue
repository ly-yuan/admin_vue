<template>
  <el-container class="container">
    <el-header class="header">
    </el-header>
    <el-container class="container">
      <el-aside class="aside" width="200px">
      </el-aside>
      <el-main class="main">
      </el-main>
    </el-container>
  </el-container>
</template>

<script>
export default {
  data () {
    return {}
  }
}
</script>

<style>
.container, .aside .aside-menu {
  height: 100%;
}

.header {
  background-color: #B3C0D1;
  line-height: 60px;
}

.aside {
  background-color: #D3DCE6;
}

.main {
  background-color: #E9EEF3;
  height: 100%;
}
</style>
