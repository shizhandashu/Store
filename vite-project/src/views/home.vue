<template>
  <div>
    {{a}}
  </div>
</template>
<script lang="ts">
import { defineComponent ,ref} from 'vue'

export default defineComponent({
  setup() {
    let a = ref("hello world")
    return {
      a
    }
  }
})
</script>
<style lang="scss" scoped></style>
