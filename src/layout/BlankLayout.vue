<template>
  <v-app id="inspire">
    <v-content>
      <v-container fluid fill-height class="bg-wrap">
        <nuxt />
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
  export default {
    name: 'BlankLayout',
    data: () => ({
      drawer: null
    }),

    props: {
      source: String
    }
  }
</script>

<style lang="scss">
.bg-wrap {
  background: url('/map-bg.png') no-repeat center center fixed;
  background-size: cover;
}
</style>
