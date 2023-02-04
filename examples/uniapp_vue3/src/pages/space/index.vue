<template>
  <view class="uno-px-2 uno-pb-10">
    <view class="uno-space-y-5">
      <!-- start: space-x  -->
      <view class="uno-text-xl uno-font-bold">
        space-x
      </view>

      <view class="uno-flex uno-h-50 uno-space-x-4">
        <view class="uno-bg-red uno-flex-1 uno-center">
          view
        </view>
        <view class="uno-bg-blue uno-flex-1 uno-center">
          view
        </view>
        <view class="uno-bg-green uno-flex-1 uno-center">
          view
        </view>
      </view>

      <view class="flex space-x-4">
        <image class="bg-red flex-1 block" src="https://img.cdn.sugarat.top/mdImg/MTY2ODA4OTc3MjcyMg==unocss-icon-gray.svg" mode="widthFix" />
        <image class="bg-blue flex-1 block" src="https://img.cdn.sugarat.top/mdImg/MTY2ODA4OTc3MjcyMg==unocss-icon-gray.svg" mode="widthFix" />
        <image class="bg-green flex-1 block" src="https://img.cdn.sugarat.top/mdImg/MTY2ODA4OTc3MjcyMg==unocss-icon-gray.svg" mode="widthFix" />
      </view>

      <view class="uno-flex uno-h-50 uno-space-x-4">
        <text class="uno-bg-red uno-flex-1 uno-center">
          text
        </text>
        <text class="uno-bg-blue uno-flex-1 uno-center">
          text
        </text>
        <text class="uno-bg-green uno-flex-1 uno-center">
          text
        </text>
      </view>

      <view class="uno-flex uno-h-50 uno-space-x-4">
        <button class="uno-bg-red uno-flex-1 uno-center">
          button
        </button>
        <button class="uno-bg-blue uno-flex-1 uno-center">
          button
        </button>
        <button class="uno-bg-green uno-flex-1 uno-center">
          button
        </button>
      </view>
      <!-- end: space-x  -->

      <!-- start  -->
      <view class="uno-text-xl uno-font-bold">
        使用 flex-row-reverse 元素倒序, 使用 space-x-reverse 间隔来确保每个元素被添加到正确的一侧
      </view>

      <view class="uno-space-x-4 uno-space-x-reverse uno-flex-row-reverse uno-flex uno-items-center">
        <view class="uno-bg-red uno-center uno-flex-1">
          view
        </view>
        <view class="uno-bg-blue uno-center uno-flex-1">
          view
        </view>
        <view class="uno-bg-green uno-center uno-flex-1">
          view
        </view>
      </view>
      <!-- end  -->

      <!-- start: space-y  -->
      <view class="uno-text-xl uno-font-bold">
        space-y
      </view>

      <view class="space-y-4">
        <view class="uno-bg-red uno-flex-1 uno-center">
          view
        </view>
        <view class="uno-bg-blue uno-flex-1 uno-center">
          view
        </view>
        <view class="uno-bg-green uno-flex-1 uno-center">
          view
        </view>
      </view>
      <!-- end: space-y  -->

      <!-- start  -->
      <view class="uno-text-xl uno-font-bold">
        space-(number)rpx
      </view>

      <view class="uno-space-y-20rpx">
        <view class="uno-bg-red uno-flex-1 uno-center">
          view
        </view>
        <view class="uno-bg-blue uno-flex-1 uno-center">
          view
        </view>
        <view class="uno-bg-green uno-flex-1 uno-center">
          view
        </view>
      </view>
      <!-- end  -->
    </view>
  </view>
</template>

<style>

</style>
