<template>
  <nav class="nav-bar mobile">
    <Links to="/" text="Home" />
    <Links to="/" text="New" />
    <Links to="/" text="Popular" />
    <Links to="/" text="Trending" />
    <Links to="/" text="Categories" />
  </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Links } from '../atoms'

export default defineComponent({
  name: 'NavbarV',
  components: { Links }
})
</script>

<style lang="scss" scoped>
.nav-bar {
  display: block;
}
</style>
