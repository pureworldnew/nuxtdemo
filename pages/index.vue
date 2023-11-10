<template>
  <log-in />
</template>
<script lang="ts">
import Vue from 'vue'
import LogIn from '../components/LogIn.vue'

export default Vue.extend({
  components: { LogIn },
  name: 'IndexPage',
})
</script>
