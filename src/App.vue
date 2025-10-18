<script>
import Header from './components/Header.vue'
import AboutUsContent from './components/AboutUsContent.vue'
import ImageContent from './components/ImageContent.vue'
import PartnersContent from './components/PartnersContent.vue'
import CardsContent from './components/CardsContent.vue'
import QuizContent from './components/QuizContent.vue'
import UpdatesContent from './components/UpdatesContent.vue'
import Footer from './components/Footer.vue'

export default{
  components:{
    Header,
    AboutUsContent,
    ImageContent,
    PartnersContent,
    CardsContent,
    QuizContent,
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
  <QuizContent />
  <UpdatesContent />
  <Footer />
</template>

<style scoped></style>
