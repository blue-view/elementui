<template>
  <div class="checkBox">
    <el-row>
      <el-checkbox v-model="checked">备选项</el-checkbox>
    </el-row>
    <el-row>
      <el-checkbox v-model="checked1" disabled>备选项1</el-checkbox>
      <el-checkbox v-model="checked2" disabled>备选项</el-checkbox>
    </el-row>
    <el-row>
      <el-checkbox-group v-model="checkList">
        <el-checkbox label="复选框 A"></el-checkbox>
        <el-checkbox label="复选框 B"></el-checkbox>
        <el-checkbox label="复选框 C"></el-checkbox>
        <el-checkbox label="禁用" disabled></el-checkbox>
        <el-checkbox label="选中且禁用" disabled></el-checkbox>
      </el-checkbox-group>
    </el-row>
  </div>
</template>

<script>
export default {
  data() {
    return {
      checked: true,
      checked1: false,
      checked2: true,
      checkList: ["选中且禁用", "复选框 A"]
    };
  }
};
</script>


