<template>
    <div>
        Hello I'm route /products/id
        {{ product }}
    </div>
</template>

<script>
// import { mapState } from 'vuex'

export default {
  computed: {
    product () {
      return this.$store.getters.getProductById(this.$route.params.id)
    }
  }
}
</script>

<style scoped>
</style>
