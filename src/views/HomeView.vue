<template>
  <v-container fluid class="mx-0 px-0 pt-0 h-100">
    <v-row class="mx-0 px-0 mt-0 pt-0 h-100">
      <v-col class="mx-0 px-0 mt-0 pt-0 hero-banner">
        <v-img
          height="100%"
          src="/images/home_banner_2.jpg"
          gradient="rgba(0, 0, 0, .42), rgba(0, 0, 0, .40)"
        >
        <v-layout
          fill-height
          align-center
          pa-3
        >
          <v-flex
            xs12
            md10
            offset-md2
          >
            <h1 class="display-3 font-weight-light white-text">
              QwikGeo
            </h1>
            <div class="display-7 text-uppercase pl-2 mb-4 mt-2 white-text">
              A state of the art geospatial platform for Location Services and GeoAnalytics.
            </div>
          </v-flex>
        </v-layout>
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

.white-text {
  color: #fff !important;
}

.hero-banner{
  height: 50vh;
}

.h-100 {
  height: 100%;
}

@media only screen and (max-width: 600px) {
  .hero-banner{
    height: 100vh;
  }
}

</style>
