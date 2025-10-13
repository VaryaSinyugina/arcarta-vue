<script>
import Header from './components/Header.vue'
import AboutUsContent from './components/AboutUsContent.vue'
import ImageContent from './components/ImageContent.vue'
import PartnersContent from './components/PartnersContent.vue'

export default{
  components:{
    Header,
    AboutUsContent,
    ImageContent,
    PartnersContent
  }
}
</script>

<template>
  <Header />
  <AboutUsContent />
  <PartnersContent />
  <ImageContent />
</template>

<style scoped></style>
