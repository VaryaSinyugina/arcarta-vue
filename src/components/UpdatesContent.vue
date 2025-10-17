<template>
    <div class="updates">
        <div class="updates-icon">
            <icon-updates></icon-updates>
        </div>   
        <div class="updates-cont">
            <h3>Art world insight.</h3>
            <p>Receive our newsletter direct to your inbox to follow updates to legislation and the EU art-market's response.</p>
            <v-text-field
                append-inner-icon="mdi-arrow-right-circle"
                variant="outlined"
                class="text-input"
                width="380"
            >
                Your email
            </v-text-field>
        </div>
    </div>
</template>

<script>
import IconUpdates from './icons/IconUpdates.vue'

export default {
    components:{
        IconUpdates,
    }
}
</script>

<style>
.updates{
    width: 1200px;
    height: 413px;
    background-color: #FAF7F3;
    display: flex;
    flex-wrap: nowrap;
    justify-self: center;
    margin-bottom: 145.91px;
}

.updates-icon{
    display: flex;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;
    margin-left: 60px;
}

.updates-cont{
    width: 550px;
    height: 272px;
    margin: 69.64px 193px 71.36px 51px 
}

.updates-cont h3 {
    font-weight: 700;
    font-size: 40px;
    line-height: 54px;
    letter-spacing: 0%;
    color: #1A1918;
    margin-top: 19.36px;
}

.updates-cont p {
    font-weight: 500;
    font-size: 20px;
    line-height: 32px;
    letter-spacing: 0%;
    color: #322F2E;
    margin-top: 24px;
    margin-bottom: 30.64px;
}

.text-input{
    background-color: #FFFFFF;
    height: 55px;
}
</style>