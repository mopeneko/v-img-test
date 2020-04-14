<template>
  <v-app>
    <v-app-bar app>
      <v-app-bar-nav-icon />
    </v-app-bar>

    <v-content>
      <v-container fluid>
        <advertisement
          src="//dummyimage.com/725x408/ff0000/000000&text=%E5%BA%83%E5%91%8A"
        />
      </v-container>
    </v-content>
  </v-app>
</template>

<script lang="ts">
import { Vue, Component } from "vue-property-decorator";
import Advertisement from "./components/Advertisement.vue";

@Component({
  components: {
    Advertisement
  }
})
export default class App extends Vue {}
</script>
