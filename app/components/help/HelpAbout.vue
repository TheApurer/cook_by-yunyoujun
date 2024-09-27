<template>
  <FAQItem :default-open="true" title="关于">
    <div text-left>
      <ul>
        <li>
          它诞生于 2024 年 1 月，将近春节期间，张某因突感厨艺精进，欲做年夜饭于亲朋好友🥳
        </li>
        <li>
          但可谓拔剑四顾心茫然，完全不知道该做什么菜🤔
        </li>
        <li>
          于是历经千难万险，佐以各种开源大佬的框架和帮助支持故得此[食用手册]😍！
        </li>
        <li>
          而如今加以改进方可展示于职业技能大赛前以供评委欣赏👍~
        </li>
        <li>
          <div class="inline-flex items-center justify-center">
            代码仓库：<a class="inline-flex items-center justify-center" href="https://github.com/TheApurer/cook" target="_blank">
              <div m="r-1" i-ri-github-line inline-flex />TheApurer/Cook</a>
          </div>
        </li>
        <li>
          <div class="inline-flex items-center justify-center">
            菜谱视频来源：
            <a class="inline-flex items-center text-sm text-blue-600 dark:text-blue-400" href="https://docs.qq.com/sheet/DQk1vdkhFV0twQVNS" target="_blank">
              <div m="r-1" i-ri-bilibili-line inline-flex />
              <span class="inline-flex">食用手册大全</span>
            </a>
          </div>
        </li>
      </ul>
    </div>
  </FAQItem>
</template>
<script setup lang="ts">
</script>