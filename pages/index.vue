<template>
  <el-container>
    <el-main>
      <div>
        <div id="welcome">
          <h1>Welcome to PumpkinSMP!</h1>
          <p>Welcome to PumpkinSMP! PumpkinSMP is a crossplay Minecraft SMP.</p>
          <img src="@/assets/images/logo.png" />
        <el-descriptions title="Connection Information">
          <el-descrption-item label="Hostname">play.pumpkinsmp.fun</el-descrption-item>
          <el-descrption-item label="Port (Bedrock Edition)">19132</el-descrption-item>
        </el-descriptions>
        <b>NOTE: You do not need to add a port for Java Edition, it will figure it out automatically.</b>
        </div>
      </div>
    </el-main>
  </el-container>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
})
</script>
