<template>
  <div class="container">
    <h3 class="header"></h3>
    <div class="card-container"></div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
    .container {
        padding: 2rem 0;
    }
    .header {
        font-weight: 700;
        font-size: 1.5rem;
        margin-bottom: 2rem;
    }
    .card-container {
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
    }
</style>
