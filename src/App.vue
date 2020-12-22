<template>
  <home></home>
</template>

<script lang="ts">
import Vue from 'vue';
import home from './views/Home.vue'

export default Vue.extend({
  name: 'App',

  components: {
    home
  },

  data: () => ({
    //
  }),
});
</script>
