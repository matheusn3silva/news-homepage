<template>
  <a :href="to" class="links">{{ text }}</a>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'LinksV',
  props: {
    text: { type: String, required: true },
    to: { type: String, required: true }
  }
})
</script>

<style lang="scss" scoped>
@import '@/assets/scss/ColorPallete.scss';
.links {
  font-size: 1.4rem;
  color: $very-dark-blue;
  text-transform: capitalize;
  text-decoration: none;
}
</style>
