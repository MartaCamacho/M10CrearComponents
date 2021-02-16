<template>
  <div class="Padre">
   <p>{{menssage}}</p>
    <Hijo></Hijo>
  </div>
</template>

<script>
import Hijo from './Hijo.vue';

export default {
    components: {
    Hijo
  },
  data() {
      return {
          menssage: 'Soc el Pare'
      }
  }
}
</script>

<style scoped>
</style>