<template>
  <div class="app">
    <Navbar />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Navbar } from '@/components/molecules'

export default defineComponent({
  components: { Navbar }
})
</script>

<style lang="scss" scoped>
.app {
  width: 300px;
}
</style>
