<script lang="ts" setup>
import { NButton } from 'naive-ui'
</script>

<template>
  <div class="flex h-full">
    <div class="px-4 m-auto space-y-4 text-center max-[400px]">
      <h1 class="text-4xl text-slate-800 dark:text-neutral-200">
        错误
      </h1>
      <p class="text-base text-slate-500 dark:text-neutral-400">
        请使用快指令APP进行访问
      </p>
      <div class="flex items-center justify-center text-center">
        <div class="w-[300px]">
          <img src="../../../icons/404.svg" alt="404">
        </div>
      </div>
      <NButton type="primary" tag="a" href="https://www.emwcloud.com.cn/rpa">
        去下载
      </NButton>
    </div>
  </div>
</template>
