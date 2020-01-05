<template>
  <div class="container">

  </div>
</template>

<script>
  export default {
    data() {
      return {
        user: {
          name: 'andrew',
          age: 14,
          class: 'susi'
        }
      }
    },
    methods: {
      showName() {
        console.log('name...')
        this.user.name = 'bily'
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>