<template>
  <v-parallax dark :src="heroData.hero.heroImgSrc">
    <v-row align="center" justify="center">
      <v-col style="color: #155555;">
        <h1 class="display-2 font-weight-bold mb-4 text-center">{{heroData.hero.heroTitle}}</h1>
        <br />
        <h4 class="subheading text-center">{{heroData.hero.heroSubtitle}}</h4>
      </v-col>
    </v-row>
  </v-parallax>
</template>

<script>
import heroData from "~/data/hero.yml";
export default {
  data() {
    return {
      heroData
    };
  }
};
</script>