<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <p>Home</p>
      <p>IsLogged in: {{ $auth.loggedIn }}</p>
      <p>Username: {{ $auth.user.name }}</p>
    </v-col>
  </v-row>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
