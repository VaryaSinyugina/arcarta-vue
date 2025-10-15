<template>
    <div class="partners-images">
        <div class="images-item">
            <img src="@/assets/img/colnaghi-img.png" alt="Colnaghi">
        </div>
        <div class="images-item">
            <img src="@/assets/img/luxembourg-img.png" alt="Luxembourg + CO.">
        </div>
        <div class="images-item">
            <img src="@/assets/img/tomasso-img.png" alt="Tomasso Brothers">
        </div>
        <div class="images-item">
            <img src="@/assets/img/cristea-img.png" alt="Cristea Roberts Gallary">
        </div>
    </div>
    <div class="d-flex justify-center">
        <v-btn
            class="text-none font-weight-black mt-5"
            size="large"
            append-icon="mdi-arrow-right-circle"
            variant="text"
            color="#C47344"
        >
            What is Arcarta?
        </v-btn>
    </div>
</template>

<style>
.partners-images{
    display: flex;
    flex-wrap: nowrap;
    justify-content: center;
    margin-top: 52px;
}

.images-item{
    width: 255px;
    height: 95px;
    margin-right: 35px;
}

.images-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;	
}

.btn-arrow-wia{
    color: #C47344;
    font-weight: 700;
    font-size: 16px;
    line-height: 20px;
    letter-spacing: 0%;
    display: flex;
    flex-wrap: nowrap;
    justify-content: center;
    margin-top: 31px;
}
</style>