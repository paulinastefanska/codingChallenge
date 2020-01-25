<template>
  <v-container class="home">
    <v-layout align-center column pa-10>
      <div class="display-2 font-weight-black text-center">Welcome To Users App</div>
      <v-btn to="/users" class='ma-2' fab x-large color='warning'>
        <v-icon>mdi-account-circle</v-icon>
      </v-btn>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: 'home'
}
</script>
