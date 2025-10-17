<script>
import Header from './components/Header.vue'
import AboutUsContent from './components/AboutUsContent.vue'
import ImageContent from './components/ImageContent.vue'
import PartnersContent from './components/PartnersContent.vue'
import CardsContent from './components/CardsContent.vue'
import UpdatesContent from './components/UpdatesContent.vue'
import Footer from './components/Footer.vue'

export default{
  components:{
    Header,
    AboutUsContent,
    ImageContent,
    PartnersContent,
    CardsContent,
    UpdatesContent,
    Footer
  }
}
</script>

<template>
  <Header />
  <AboutUsContent />
  <PartnersContent />
  <ImageContent />
  <CardsContent />
  <UpdatesContent />
  <Footer />
</template>

<style scoped></style>
