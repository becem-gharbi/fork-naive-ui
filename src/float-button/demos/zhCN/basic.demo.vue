<markdown>
  # 基础用法
</markdown>

<template>
  <div style="height: 200px; transform: translate(0)">
    <n-float-button :right="0" :bottom="0">
      <n-icon :size="24">
        <cash-icon />
      </n-icon>
    </n-float-button>
    <n-float-button :left="0" :bottom="0">
      <n-icon :size="24">
        <cash-icon />
      </n-icon>
    </n-float-button>
    <n-float-button :right="0" :top="0">
      <n-icon :size="24">
        <cash-icon />
      </n-icon>
    </n-float-button>
    <n-float-button :left="0" :top="0">
      <n-icon :size="24">
        <cash-icon />
      </n-icon>
    </n-float-button>
  </div>
</template>

<script lang="ts">
import { CashOutline as CashIcon } from '@vicons/ionicons5'
import { defineComponent } from 'vue'

export default defineComponent({
  components: {
    CashIcon
  }
})
</script>
