<template>
  <v-container fluid class="mx-0 px-0 pt-0 h-100">
    <v-row class="mx-0 px-0 mt-0 pt-0">
      <v-col cols="12" class="mx-0 px-0 mt-0 pt-0 hero-banner">
        <v-img
          height="100%"
          src="/images/home_banner_2.jpg"
          gradient="rgba(0, 0, 0, .52), rgba(0, 0, 0, .52)"
        >
        <v-layout
          align-center
          px-3
          pt-10
        >
          <v-flex
            xs12
            md10
            pt-10
          >
            <h1 class="display-3 font-weight-light white-text pt-10">
              QwikGeo
            </h1>
            <h5 class="text-uppercase pl-2 mb-4 mt-2 white-text">
              A state of the art geospatial platform for Location Services and GeoAnalytics.
            </h5>
          </v-flex>
        </v-layout>
        </v-img>
      </v-col>
    </v-row>
    <!-- <v-row class="mx-0 px-0 mt-0">
      <v-col cols="8" class="text-center pt-6">
        <v-card class="pa-4 rounded-xl" elevation="20">
          <v-icon
            x-large
            style="font-size: 8rem"
          >
            mdi-database
          </v-icon>
        </v-card>
      </v-col>
    </v-row> -->

    <v-row class="mx-0 px-0 mt-0">
      <v-col cols="12" md="8" class="text-center pt-3">
        <div>QwikGeo makes it easy for you to answer where and why things are happening.</div>
      </v-col>
      <v-col cols="12" md="4">
        <v-img src="/images/home_3.jpg" height="300">

        </v-img>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'HomeView',
}
</script>

<style>

.hero-banner{
  height: 50vh;
}

@media only screen and (max-width: 600px) {
  .hero-banner{
    height: 100vh;
  }
}

</style>
