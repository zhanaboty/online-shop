<template>
  <div class="v-main-wrapper">
      <v-catalog/>
      <v-card/>
  </div>
</template>

<script>
import vCatalog from './v-catalog.vue'
import vCard from './v-card.vue'

export default {
    name: 'v-main-wrapper',
    components: {
        vCatalog,
        vCard
    },
    props:{},
    data() {
        return{

        }
    },
    computed: {},
    methods: {},
    watch: {},
    mounted() {

    }
}
</script>

<style>
    .v-main-wrapper {
        max-width: 900px;
        margin: 0 auto;
    }
</style>