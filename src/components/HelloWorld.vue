<!--
 * @Author: 阿馨
 * @Date: 2020-07-17 18:03:09
 * @LastEditTime: 2020-10-10 14:16:57
 * @Descripttion: 说下使用场景，是用来干什么的
 * @Props: 参数名 类型 [选填/必填] 说明 默认值
 * @Events: 事件名($emit触发的事件) 说明(最好把参数说明下)
 * @Example: 用法举例
-->
<template>
  <div class="hello">
    <el-table :data="tableData" style="width: 100%">
      <el-table-column prop="date" label="日期" width="180"></el-table-column>
      <el-table-column prop="name" label="姓名" width="180"></el-table-column>
      <el-table-column prop="address" label="地址"></el-table-column>
      <el-table-column prop="address" label="哈哈"></el-table-column>
      <el-table-column prop="address" label="啦啦"></el-table-column>
       <el-table-column prop="address" label="啦啦"></el-table-column>
       <el-table-column prop="address" label="啦啦"></el-table-column>
       <el-table-column prop="address" label="啦啦"></el-table-column>
       <el-table-column prop="address" label="啦啦"></el-table-column>
       <el-table-column prop="address" label="啦啦"></el-table-column>
       <el-table-column prop="address" label="啦啦"></el-table-column>
       <el-table-column prop="address" label="嘻嘻"></el-table-column>
       <el-table-column prop="address" label="嘿嘿"></el-table-column>
    </el-table>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      tableData: [
        {
          date: '2016-05-02',
          name: '阿馨',
          address: '北京'
        }
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
