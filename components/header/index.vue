<template>
  <header class="header">
    <h1 class="header__title">Chii Mobi</h1>
  </header>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'Header',
})
</script>

<style lang="scss" scoped>
.header {
  text-align: center;
}
.header__title {
  color: #780505;
}
</style>
