<script>
import Header from './components/Header.vue'
import AboutUsContent from './components/AboutUsContent.vue'
import ImageContent from './components/ImageContent.vue'
import PartnersContent from './components/PartnersContent.vue'
import CardsContent from './components/CardsContent.vue'

export default{
  components:{
    Header,
    AboutUsContent,
    ImageContent,
    PartnersContent,
    CardsContent
  }
}
</script>

<template>
  <Header />
  <AboutUsContent />
  <PartnersContent />
  <ImageContent />
  <CardsContent />
</template>

<style scoped></style>
