<template>
    <header>
        <div class="logo">
            <icon-acarta></icon-acarta> 
        </div>
        <div class="header-links">
            <a href="#">What is Acarta?</a>
            <a href="#">Solutions</a>
            <a href="#">Resources</a>
            <a href="#">FAQs</a>
            <a href="#">Contact</a>
            <a href="#">Login</a>
            <v-btn class="btn-get-started">Get Started</v-btn>
        </div>
    </header>
</template>

<script>
import IconAcarta from './icons/IconAcarta.vue'

export default{
    components:{
        IconAcarta
    }
}
</script>

<style>
header{
    display: flex;
    width: 1300px;
    height: 90px;
    margin-top: 16px;
    margin-left: 70px;
    margin-right: 70px;
    justify-content: space-between;
}

.logo{
    margin-top: 31px;
}

.header-links{
    display: flex;  
    margin-top: 15px;
    
}

.header-links a{
    font-weight: 700;
    font-size: 15px;
    line-height: 20px;
    letter-spacing: 0%;
    color: #322F2E;
    margin-top: 18px;
    margin-right: 45px;
    text-decoration: none;
}

.btn-get-started{
    color: #ffffff;
    background-color: #C47344;
    border-radius: 50px;
    width: 129px;
    height: 47px;
    margin-top: 7px;
    display: flex;
    flex-wrap: nowrap;
    align-items: center;
    justify-content: center;
}
</style>