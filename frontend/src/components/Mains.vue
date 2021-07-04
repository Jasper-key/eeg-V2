<template>
  <div id="mainFirstDiv">
    <div class="header">
      <div class="headerLeft">
        <img src=".././assets/logo.png">
      </div>
      <div class="headerMain">
        ｜睡眠分期自动判读系统
      </div>
      <div class="headerRight">
        <el-switch
            v-model="value"
            active-color="#13ce66"
            inactive-color="#ff4949"
        >
        </el-switch>
        <span v-if="value">
        浅色模式
      </span>
        <span v-else>
        深色模式
      </span>
      </div>
    </div>
    <div class="containerMain">
      <div class="right">

      </div>
      <div class="left">

      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Mains",
  data() {
    return {
      value: true,
    }
  },
}
</script>

<style scoped>
#mainFirstDiv {
  width: 100%;
  height: 100%;
}

.containerMain {
  display: flex;
  width: 100%;
  height: 92%;
}

.header {
  width: 100%;
  height: 8%;
  vertical-align: middle;
  display: table;
  border-bottom: 1px solid #CCCCCC;
}

.right {
  width: 80%;
  height: 100%;
}

.left {
  width: 20%;
  height: 100%;
}

.headerLeft {
  display: table-cell;
  vertical-align: middle;
  text-align: right;
  width: 20%;
}

.headerMain {
  display: table-cell;
  width: 65%;
  font-family: PingFang SC;
  font-size: 26px;
  vertical-align: middle;
}

.headerRight {
  display: table-cell;
  vertical-align: middle;
}
</style>
