<template>
  <div class="row">
    <div class="col-12 col-md-3">
      <h1>Formularios</h1>
    </div>
    <div class="col-12 col-md-6">
      <img :src="url" width="150">
    </div>
  </div>
  <hr>
</template>

<script>
export default {
  data: () => ({
    url: "https://v2.vuejs.org/images/logo.svg",
  }),
}
</script>
