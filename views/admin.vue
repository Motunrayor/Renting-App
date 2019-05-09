<template>
  <div class="admin">
    <navigation />
    <adminCom />
  </div>
</template>
<script>
import navigation from '@/components/navBar.vue'
import adminCom from '@/components/adminCom.vue'

export default {
  name: 'admin',

  components: {
    navigation,
    adminCom,
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
