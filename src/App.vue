<template>
  <v-app>
    <v-content>
      <v-container>
        <v-date-range v-model="range"></v-date-range>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      range: undefined
    };
  }
};
</script>
