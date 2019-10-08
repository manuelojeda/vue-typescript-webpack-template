<template>
  <div>
    {{ hola }}
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  data () {
    return {
      hola: 'Hola Mundo con Vue y TypeScript' as string
    }
  }
})
</script>
