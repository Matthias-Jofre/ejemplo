<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card class="example">
        <Example />
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
import Example from '../components/example.vue';
export default {
    name: "TestPage",
    components: { Example }
};
</script>

<style scoped>

</style>
