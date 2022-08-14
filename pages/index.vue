<template>
  <el-container>
    <el-main>
      <div>
        <div id="welcome">
          <h1>Welcome to PumpkinSMP!</h1>
          <p>Welcome to PumpkinSMP! PumpkinSMP is a crossplay Minecraft SMP.</p>
          <img src="@/assets/images/logo.png" />
        <el-descriptions title="User Info">
          <el-descriptions-item label="Username">kooriookami</el-descriptions-item>
          <el-descriptions-item label="Telephone">18100000000</el-descriptions-item>
          <el-descriptions-item label="Place">Suzhou</el-descriptions-item>
          <el-descriptions-item label="Remarks">
            <el-tag size="small">School</el-tag>
          </el-descriptions-item>
          <el-descriptions-item label="Address">No.1188, Wuzhong Avenue, Wuzhong District, Suzhou, Jiangsu Province</el-descriptions-item>
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
