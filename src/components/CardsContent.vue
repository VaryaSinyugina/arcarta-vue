<template>
  <v-container class="d-flex flex-wrap justify-center pa-10">
    <!--                                   Card 1                                     -->
    <v-card
      class="pa-8 text-center me-4"
      elevation="1"
      width="496.9"
      height="498"
      rounded="m"
      color="#FFFAF2"
      
    >
      <!-- <v-img
        src="@/assets/img/card1-img.png"
        alt="Art dealers illustration"
        contain
        height="120"
        class="mb-6"
      ></v-img> -->
      <img class="card-img" src="@/assets/img/card1-img.png" alt="Card 1 Image">

      <v-card-title class="text-h3 font-weight-bold" color="#322F2E">
        For Art Dealers
      </v-card-title>

      <v-card-subtitle class="text-body-1 text-h4 mb-6">
        Galleries and independent art dealers
      </v-card-subtitle>

      <v-btn
        color="black"
        variant="text"
        rounded="xl"
        size="large"
        class="text-none"
        border
      >
        Learn More
      </v-btn>
    </v-card>
    <!--                                   Card 2                                     -->
    <v-card
      class="pa-8 text-center"
      elevation="1"
      width="496.9"
      height="498"
      rounded="m"
      color="#FFFAF2"
      
    >
      <img class="card-img" src="@/assets/img/card2-img.png" alt="Card 1 Image">

      <v-card-title class="text-h3 font-weight-bold" color="#322F2E">
        For Advisors
      </v-card-title>

      <v-card-subtitle class="text-body-1 text-h4 mb-6">
        Advisors, agents and consultants
      </v-card-subtitle>

      <v-btn
        color="black"
        variant="text"
        rounded="xl"
        size="large"
        class="text-none"
        border
      >
        Learn More
      </v-btn>
    </v-card>
    <!--                                   Card 3                                     -->
    <v-card
      class="pa-8 text-center me-4 mt-4"
      elevation="1"
      width="490"
      height="578"
      rounded="m"
      color="#FFFAF2"
      
    >
      <img class="card-img" src="@/assets/img/card3-img.png" alt="Card 1 Image">

      <v-card-title class="text-h3 font-weight-bold" color="#322F2E">
        For Auctioneers
      </v-card-title>

      <v-card-subtitle class="text-body-1 text-h4 mb-6">
        Online and offline auctioneers
      </v-card-subtitle>

      <v-btn
        color="black"
        variant="text"
        rounded="xl"
        size="large"
        class="text-none"
        border
      >
        Learn More
      </v-btn>
    </v-card>
    <!--                                   Card 4                                     -->
    <v-card
      class="pa-8 text-center mt-4"
      elevation="1"
      width="490"
      height="578"
      rounded="m"
      color="#FFFAF2"
      
    >
      <img class="card-img" src="@/assets/img/card4-img.png" alt="Card 1 Image">

      <v-card-title class="text-h3 text-wrap font-weight-bold" color="#322F2E">
        For Buyers & Collectors
      </v-card-title>

      <v-card-subtitle class="text-body-1 text-wrap text-h4 mb-6">
        Receiving Invoices, making card payments and sending your ID and address documents
      </v-card-subtitle>

      <v-btn
        color="black"
        variant="text"
        rounded="xl"
        size="large"
        class="text-none"
        border
      >
        Learn More
      </v-btn>
    </v-card>
  </v-container>
</template>


<style scoped>
.card-img{
    width: 223.1px;
    height: 220px;
    object-fit: cover;
}
</style>
