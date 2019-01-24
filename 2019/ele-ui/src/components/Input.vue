<template>
  <div class="input">
    <el-row>
      <el-col>
        <el-input v-model="input" placeholder="请输入内容"></el-input>
      </el-col>
    </el-row>
    <el-row>
      <el-col>
        <el-input placeholder="请输入内容" v-model="input1" :disabled="true"></el-input>
      </el-col>
    </el-row>
    <el-row>
      <el-col>
        <el-input placeholder="请输入内容" v-model="input10" clearable></el-input>
      </el-col>
    </el-row>
    <el-row>
      <el-col>
        <div class="demo-input-suffix">属性方式：
          <el-input placeholder="请选择日期" suffix-icon="el-icon-date" v-model="input2"></el-input>
          <el-input placeholder="请输入内容" prefix-icon="el-icon-search" v-model="input21"></el-input>
        </div>
      </el-col>
    </el-row>
    <el-row>
      <el-col>
        <div class="demo-input-suffix">slot 方式：
          <el-input placeholder="请选择日期" v-model="input22">
            <i slot="suffix" class="el-input__icon el-icon-date"></i>
          </el-input>
          <el-input placeholder="请输入内容" v-model="input23">
            <i slot="prefix" class="el-input__icon el-icon-search"></i>
          </el-input>
        </div>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {
  data() {
    return {
      input: "",
      input1: "",
      input10: "",
      input2: "",
      input21: "",
      input22: "",
      input23: ""
    };
  }
};
</script>


