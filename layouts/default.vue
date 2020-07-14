<template>
    <nuxt />
</template>

<script>

import Vue from "vue";
import Cloudinary, { CldImage } from "cloudinary-vue";

Vue.use(Cloudinary, {
  configuration: { cloudName: "dxvbzmqfs" },
  components: [ CldImage ]
});

import 'buefy/dist/buefy.css'

export default {

}
</script>
