<template>
  <div>
    <div class="w-full">
      <CommonHeader>
        帮助
      </CommonHeader>

      <InstallPwa />

      <div class="mx-auto max-w-md w-full rounded-2xl p-2" text-left>
        <FAQItem title="未来计划？">
          计划增加新功能，如自定义菜谱🍳
        </FAQItem>

        <FAQItem title="什么是模式？">
          <ul>
            <li><b>模糊匹配</b>：展示所有含当前选中任意食材的菜谱😉️</li>
            <li><b>精准匹配</b>：展示所有含当前选中所有食材的菜谱🧐</li>
            <li><b>生存模式</b>：展示当前选中食材即可制作的所有菜谱🥹</li>
          </ul>
        </FAQItem>

        <FAQItem title="如何快速清空所选食材和工具?">
          <div inline-flex items-center justify-center>
            点击顶部 <div i-mdi-pot-steam-outline mx-1 inline-block /> 图标即可🤗
          </div>
        </FAQItem>

        <FAQItem title="还没想到有什么问题，先占个位置">
          <blockquote>
            浅色浅色浅色
          </blockquote>
          <br>
          <ol>
            <li>
              <b>标题一</b>
              <ol>
                <li>
                  小标题一
                </li>
                <li>
                  小标题二
                </li>
              </ol>
            </li>
            <li>
              <b>标题二</b>
              <ul>
                <li>点一下，叽里呱啦</li>
                <li>这个标签之间可以放代码<code>Cmd + Shift + R</code></li>
              </ul>
            </li>
          </ol>
        </FAQItem>

        <hr h="1" my="4" bg-black>

        <HelpAbout />

        <FAQItem title="关于我">
          <div text-left>
            我的微信「景年🍰」😎 <br>会分享一些生活❤️和读后感📕
            <img src="/name.jpg" style="width: 400px; height: auto;">
          </div>
        </FAQItem>
      </div>
    </div>
  </div>
</template>
