<template>
  <div>
    <input type="email" v-model="email" />
    <button class="btn outline primary bg-gray" @click="onClick">Click</button>
  </div>
</template>
<script>
export default {
  data() {
    return {
      email: '',
    }
  },

  methods: {
    onClick() {
      console.log(this.email, this.$axios)
    },
  },
}
</script>
<style lang=""></style>
