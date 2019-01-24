<template>
  <div class="icon">
    <i class="el-icon-edit"></i>
    <i class="el-icon-share"></i>
    <i class="el-icon-delete"></i>
    <i class="el-icon-info"></i>
    <i class="el-icon-error"></i>

    <el-button type="primary" icon="el-icon-search">搜索</el-button>
  </div>
</template>

<script>
export default {
  name: "Icon",
  props: {
    msg: String
  }
};
</script>


