<script lang="ts" setup>
import { isClient } from '@vueuse/core'

const displayICP = ref(true)

onBeforeMount(() => {
  if (isClient)
    displayICP.value = ['cook.yunyoujun.cn', 'localhost', '127.0.0.1'].includes(window.location.hostname)
})
</script>

<template>
  <div p="4 t-2" class="flex flex-col items-center justify-center" text="sm">
    <CurrentVersion />
    <a v-if="displayICP" opacity="80" class="flex" href="https://beian.miit.gov.cn/" target="_blank">
      害得我殚精竭虑，忙的我废寝忘食
    </a>
    <div m="t-2" class="inline-flex items-center justify-center" text="xs">
      <a class="inline-flex items-center justify-center" style="color: #ea7b99" href="https://www.bilibili.com/blackboard/dynamic/306882" target="_blank">
        <span inline-flex>菜谱视频来源：</span>
        <div class="inline-flex" i-ri-bilibili-line />
        <span m="l-1" class="inline-flex" style="margin-top: 1px;">B 站</span>
      </a>
    </div>
    <div mt-2>
      本站点由Vue，TypeScript，SCSS等构成，基于Web应用框架Nuxt.js
    </div>
    <div m="t-2" opacity="80" class="flex items-center justify-center">
      ©️&nbsp;<a href="https://github.com/TheApurer/Cook" target="_blank">Cook</a>
      <div text="xs" m="x-1" i-ri-cloud-line />
      <a href="https://space.bilibili.com/299415521" target="_blank">景年🍰</a>
    </div>
  </div>
</template>
