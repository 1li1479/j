<template>
  <div class="content">
    分享到：
      <el-tooltip class="item" effect="dark" content="分享给QQ好友" >
        <el-button circle><img src="http://zixuephp.net/static/images/qqshare.png" width="25"></el-button>
      </el-tooltip>
    &nbsp
      <el-tooltip class="item" effect="dark" content="分享到QQ空间" >
        <el-button circle><img src="http://zixuephp.net/static/images/qqzoneshare.png" width="25"></el-button>
      </el-tooltip>
    </div>
</template>

<script>
    export default {
        name: "share_qzone",

  data() {
    return {
        }
      }
    }
</script>

<style scoped>
.content{
  text-align: center;
}
.item {
  margin: 1px;
}
</style>
