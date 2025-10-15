<template>
    <div class="cont">
       <div class="about-us-content">
            <div class="tag">
                <p class="tag-new">New</p>
                <p class="tag-art-report">The Art Marker Report</p>
            </div>
            <div class="info">
                <h1 class="title">Rely on us</h1>
                <p>Our Customer Due Diligence platform helps you avoid fines or losing clients due to AML while protecting you from cybercrime.</p>
                <div class="d-flex justify-center">
                   <v-btn 
                    color="#C47344"
                    rounded="xl"
                    variant="flat"
                    width="158"
                    height="47"
                    class="text-none mt-3"
                    >
                    Learn More
                    </v-btn> 
                </div>
                
            </div>
        </div> 
    </div>
    
</template>

<script></script>

<style>
.cont{
    width: 700px;
    height: 349px;
    display: flex;
    flex-wrap: nowrap;
    justify-content: center;
    justify-self: center;
    margin-top: 140px;
}

.about-us-content{
    display: flex;
    flex-wrap: nowrap;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    
}

.tag{
    display: flex;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;
    
}

.tag-new{
    color: #ffffff;
    font-weight: 700;
    font-size: 12px;
    line-height: 25px;
    letter-spacing: 0%;
    text-align: center;
    background-color: #F9A38F;
    border-radius: 20px;
    width: 51px;
    height: 25px;
    opacity: 1;

}

.tag-art-report{
    width: 188px;
    height: 25px;
    opacity: 1;
    border-radius: 20px;
    background-color: #F9EDE2;
    color: #4D4D4D;
    font-weight: 700;
    font-size: 13px;
    line-height: 25px;
    letter-spacing: 0%;
    text-align: center;
    margin-left: -10px;
}

.title{
    color: #322F2E;
    font-weight: 700;
    font-size: 110px;
    line-height: 119px;
    letter-spacing: 0%;
    text-align: center;
    margin-bottom: 10px;
    margin-top: 11px;
}

.info p{
    font-weight: 500;
    font-size: 21px;
    color: #322F2E;
    line-height: 33px;
    letter-spacing: 0%;
    text-align: center;
    width: 524px;
    height: 99px;
}
</style>