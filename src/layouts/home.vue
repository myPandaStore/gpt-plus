<!--
 * @Author: luckin 1832114807@qq.com
 * @Date: 2023-10-11 16:41:33
 * @LastEditors: luckin 1832114807@qq.com
 * @LastEditTime: 2023-10-11 21:14:49
 * @FilePath: \vitesse\src\layouts\home.vue
 * @Description:
 *
 * Copyright (c) 2023 by ${git_name_email}, All Rights Reserved.
-->
<template>
  <div class="side-bar">
    <div>主页</div>
    <div>对话</div>
    <div>文档</div>
    <div>绘画</div>
    <div>画廊</div>
    <div>写作</div>
    <div>思维导图</div>
    <div>白板</div>
    <div>签到奖励</div>
    <div>深色</div>
    <div>消息</div>
    <div>头像</div>
    <div>默认</div>
  </div>
  <main px-4 py-10 text="center gray-700 dark:gray-200">
    <RouterView />
    <TheFooter />
    <div mx-auto mt-5 text-center text-sm opacity-50>
      [Home Layout]test
    </div>
  </main>
</template>
