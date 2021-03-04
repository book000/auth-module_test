<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <p>Top page</p>
      <v-btn block @click="$router.push('/login')">Login</v-btn>
    </v-col>
  </v-row>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({})
</script>
