<template>
  <div class="properties">
    <navigation />
    <search />
    <homes />
    <Runway />
  </div>
</template>
<script>
  import navigation from '@/components/navBar.vue'
  import search from '@/components/search.vue'
  import homes from '@/components/homes.vue'
  import Runway from '@/components/Runway.vue'

export default {
  name: 'properties',

  components:{
      navigation,
      search,
      homes,
      Runway,
  },
  
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>