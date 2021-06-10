<template>
  <v-container>
    <v-row>
      <v-col v-for="count in 12" :key="count" cols="6">
        <v-card class="pa-3">
          Col
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {};
</script>

<style></style>
