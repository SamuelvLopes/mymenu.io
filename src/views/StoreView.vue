<template>
  <div>
    <h1>Bem-vindo : {{ store }}</h1>
    <!-- Outros elementos do template -->
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'StoreView',
  props: {
    store: {
      type: String,
      required: true
    }
  },
  
});
</script>
