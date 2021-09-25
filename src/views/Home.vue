<template>
  <div class="home">
    <el-input v-model="searchText" placeholder="请输入内容">
      <el-button slot="append" icon="el-icon-search" />
    </el-input>
  </div>
</template>

<script>
export default {
  name: "Home",
  data() {
    return {
      searchText: ""
    };
  }
};
</script>
