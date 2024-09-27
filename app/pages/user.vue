<script lang="ts" setup>
</script>

<template>
  <div>
    <CommonHeader>
      我的
    </CommonHeader>

    <div
      class="mx-auto max-w-md w-full"
      px-2
      text-left
    >
      <div mt-2 gap="3" grid="~ cols-3">
        <YlfIconItem to="/recipes/history" icon="i-ri-history-line" label="历史记录" />
        <YlfIconItem to="/recipes/collect" icon="i-ri-star-line" label="我的收藏" />
        <YlfIconItem to="/cookbooks" icon="i-ri-article-line" label="自定义菜谱" />
      </div>

      <YlfForm>
        <YlfFormItem icon="i-ri-settings-line" label="设置" to="/settings" />
      </YlfForm>

      <!-- <YlfForm>
        <YlfFormItem icon="i-ri-article-line" label="自定义菜谱 TODO" to="/cookbooks/" />
      </YlfForm> -->

      <YlfForm>
        <YlfFormItem icon="i-ri-question-line" label="帮助" to="/help" />
        <YlfFormItem icon="i-ri-information-line" label="关于" to="/help" />
      </YlfForm>
    </div>

    <BaseFooter mt-4 />
  </div>
</template>
