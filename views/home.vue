<template>
  <div class="home">
  <pageHeader/>
  <navigation/>
  <appCard/>
  <signup/>
  <testimonial/>
  <post/>
  <footer/>
  </div>
</template>

<script>
import navigation from '@/components/navBar.vue'
import PageHeader from '@/components/header.vue'
import appCard from '@/components/appCard.vue'
import signup from '@/components/signup.vue'
import testimonial from '@/components/testimonial.vue'
import post from '@/components/postProperty.vue'
import footer from '@/components/footer.vue'

export default {
  name: 'home',

  components:{ 
      navigation,
      PageHeader,
      appCard,
      signup,
      testimonial,
      post,
      footer,
  }
  
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
