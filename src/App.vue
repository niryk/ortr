<template>
  <v-app>
    <v-content>
      <ortr />
    </v-content>
  </v-app>
</template>

<script>
import ortr from "./components/ortr";

export default {
  name: "App",
  components: {
    ortr
  },
  data: () => ({})
};
</script>
