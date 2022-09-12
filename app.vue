<template>
  <div>
    <!-- <NuxtWelcome /> -->
    <div>
    <h1 class="text-center">Dielenske</h1>
    <h3 class="text-center">Pocasie</h3>
    <v-card width="600" class="mx-auto pa-3">
      <v-row justify="center">
      <v-icon x-large color="blue">mdi-account-circle</v-icon>
      </v-row>
      <v-card-title class="justify-center">Login</v-card-title>

      <v-text-field class="" label="username or email"></v-text-field>
      <v-text-field label="password"></v-text-field>
      <v-card-actions>
        <v-checkbox v-model="checkbox" label="REMEBER ME"></v-checkbox>
        <v-spacer></v-spacer>
        <v-text>Sign up here</v-text>
        <br />
      </v-card-actions>
      <v-row justify="center">
      <v-btn color="primary" class="text-center mb-2">Login</v-btn>
      </v-row>
    </v-card>
  </div>
  </div>
</template>
<script>

</script>
