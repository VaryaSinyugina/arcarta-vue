<template>
    <div class="quiz">
        <div class="quiz-img">
            <icon-quiz></icon-quiz>
        </div>
        <div class="quiz-info">
            <p class="tag-new">New</p>
            <h2>Does Anti-money Laundering affect you?</h2>
            <p class="descr">A short, interactive quiz to check if your art business is affected by 5AMLD regulation.</p>
            <v-btn
            width="146"
            height="47"
            rounded="xl"
            variant="outlined"
            class="text-none"
            >Take the Quiz</v-btn>
        </div>
    </div>
</template>

<script>
import IconQuiz from './icons/IconQuiz.vue'

export default {
    components: {
        IconQuiz,
    }
}
</script>

<style>
.quiz{
    width: 100%;
    height: 412px;
    display: flex;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;
    margin-bottom: 135.7px;
    margin-top: 177px;
}

.quiz-info{
    width: 470px;
    height: 390px;
    margin-left: 85px;
}

.quiz-info h2{
    font-weight: 700;
    font-size: 53px;
    line-height: 62px;
    letter-spacing: 0%;
    color: #322F2E;
    margin-top: 18px;
    margin-bottom: 25px;
}

.tag-new {
    font-weight: 700;
    font-size: 12px;
    line-height: 25px;
    letter-spacing: 0%;
    text-align: center;
    color: #FFFFFF;
    background-color: #F9A28F;
    width: 54px;
    height: 25px;
    border-radius: 20px;
}

.descr{
    font-weight: 500;
    font-size: 21px;
    line-height: 33px;
    letter-spacing: 0%;
    color: #322F2E;
    margin-bottom: 23px;
}
</style>