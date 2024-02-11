<template>
  <img :src="pathImage" class="images" />
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  props: {
    src: { type: String, required: true }
  },
  computed: {
    pathImage() {
      return require(`@/assets/images/${this.src}`)
    }
  }
})
</script>

<style lang="scss" scoped>
.images {
  width: 100%;
}
</style>
