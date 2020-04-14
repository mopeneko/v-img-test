<template>
  <v-row dense justify="center">
    <v-col cols="12" md="8" lg="8" xl="8">
      <v-img :src="src" height="40vh" contain />
    </v-col>
  </v-row>
</template>

<script lang="ts">
import { Vue, Component, Prop } from "vue-property-decorator";

@Component
export default class Advertisement extends Vue {
  @Prop()
  src!: string;
}
</script>

<style scoped>
.container {
  padding: 0;
}
</style>
