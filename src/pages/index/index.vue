<template>
  <view class="index">
    <text>{{ msg }}</text>
    <view v-html="msg"></view>
  </view>
</template>

<script>
import {ref} from 'vue'
import './index.scss'

export default {
  setup() {
    const msg = ref('Hello world')
    return {
      msg
    }
  }
}
</script>
