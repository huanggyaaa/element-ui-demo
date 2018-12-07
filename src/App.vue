<template>
  <div id="app">
    <el-button type="success">成功按钮</el-button>
    <el-button type="info" plain>信息按钮</el-button>
    <el-button type="warning" round>警告按钮</el-button>
    <el-button type="warning" icon="el-icon-star-off" circle></el-button>
    <el-button type="primary">上传<i class="el-icon-upload el-icon--right"></i></el-button>
    <hr>
    <DatePicker />
    <hr>
    <Upload />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import DatePicker from './components/elementUI/DatePicker'
import Upload from './components/elementUI/Upload'

export default {
  name: 'App',
  components: {
    HelloWorld,
    DatePicker,
    Upload
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
