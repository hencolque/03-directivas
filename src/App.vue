<template>
  <div class="container mt-3">

    <Header />
    <Formulario />
  </div>
</template>

<script>
import Formulario from './components/Formulario.vue';
import Header from './components/Header.vue';

export default {
  components: {
    Header,
    Formulario
  }
}
</script>
