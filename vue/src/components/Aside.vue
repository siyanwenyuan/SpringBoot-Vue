<template>

  <div>
    <el-menu
        style="width: 200px; min-height: 100vh"
        default-active="2"
        class="el-menu-vertical-demo"
    >


        <el-sub-menu index="1">
          <template #title>导航一</template>
          <el-menu-item index="1-4-1">选项1-1</el-menu-item>
        </el-sub-menu>


      <el-menu-item index="2">
        <el-icon><icon-menu /></el-icon>
        <span>导航二</span>
      </el-menu-item>

      <el-menu-item index="4">
        <el-icon><setting /></el-icon>
        <span>导航三</span>
      </el-menu-item>

    </el-menu>
  </div>
</template>
<script>
export default {
  name: "Aside"
}
</script>
<style scoped>

</style>
