<template>
  <Header />
</template>

<script lang="ts">
import Vue from 'vue'
import Header from '~/components/header/index.vue'

export default Vue.extend({
  name: 'IndexPage',
  components: { Header }
})
</script>
