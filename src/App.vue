<template>
  <v-app>
    <v-main>
      <footer-bar/>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

import FooterBar from "@/components/FooterBar";
export default {
  name: 'App',
  components: {FooterBar},
  data: () => ({
    //
  }),
};
</script>
