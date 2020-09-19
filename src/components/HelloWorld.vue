<template>
  <v-container class="red">
    <v-layout class="text-center">
      <v-flex>
        <v-img
          :src="require('../assets/logo.svg')"
          class="my-3"
          contain
          height="200"
        />
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<style>
 .red {
   background-color: red;
 }

 @media screen and (min-width: 1095px) {
   .red {
      padding: 4.725rem 0;
   }
 
 }

  @media screen and (min-width: 902px) and (max-width: 1094px) {
   .red {
     padding: 7.75rem 0;
   }
 }

  @media screen and (min-width: 695px) and (max-width: 901px) {
   .red {
     padding: 10.75rem 0;
   }
 }

  @media screen and (min-width: 631px) and (max-width: 694px) {
   .red {
     padding: 13.75rem 0;
   }
 }

   @media screen and (min-width: 600px) and (max-width: 630px) {
   .red {
     padding: 16.75rem 0;
   }
  }


</style>
