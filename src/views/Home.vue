<template>
  <v-container fluid class="pos-main fill-height pa-0">
    <v-row class="no-gutters flex-wrap flex-column fill-height pa-2">
      <v-col cols="auto" class="shrink">
        <pos-header />
      </v-col>
      <v-col cols="auto">
        <div class="my-2"></div>
      </v-col>
      <v-col cols="auto" class="grow">
        <pos-body />
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.pos-main {
  background-color: #d1d5db;
}
</style>

<script>
import PosHeader from "../components/POS/Header.vue";
import PosBody from "../components/POS/Body.vue";

export default {
  components: { PosHeader, PosBody },
  name: "Home",
};
</script>
