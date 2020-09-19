<template>
 <v-card height="150">
    <v-footer
      class="font-weight-medium"
      color="primary"
      dark
    >
      <v-col
        class="text-center"
        cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
      </v-col>
    </v-footer>
  </v-card>
</template>

<script>
  export default {
    
  }
</script>

<style lang="scss" scoped>

</style>
