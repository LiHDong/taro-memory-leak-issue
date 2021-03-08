<template>
  <view v-html="msg">2333</view>
</template>

<script>
import { ref } from 'vue'
import './index.css'

export default {
  setup () {
    const msg = ref(`<style > </style>`)
    return {
      msg
    }
  }
}
</script>
