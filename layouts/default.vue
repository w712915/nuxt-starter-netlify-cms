<template>
  <div class="l_container">
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
export default {}
</script>

<style>
.l_container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
footer {
  margin-top: auto !important;
}
</style>
