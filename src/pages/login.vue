<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <p>Login</p>
    </v-col>
  </v-row>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  created() {
    this.$auth.loginWith('github')
  },
})
</script>
