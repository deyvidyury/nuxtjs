<template>
  <section class="container">
    <nuxt-link to="/users">Users</nuxt-link>
    <br>
    <button @click="onLoadProducts">Load Products</button>
  </section>
</template>

<script>

export default {
  methods: {
    onLoadProducts() {
      this.$router.push('/products');
    }
  }
}
</script>

