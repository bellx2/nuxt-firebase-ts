<template>
  <div class="container">
    <div
      class="p-6 max-w-sm mx-auto bg-white rounded-xl shadow-md flex items-center space-x-4"
    >
      <div>
        <div lass="text-xl font-medium text-black">Test Message2</div>
        <p class="text-gray-500">You have a new tailwind css message!</p>
        <el-button>Test ElementsUI Button !!! </el-button>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({});
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
