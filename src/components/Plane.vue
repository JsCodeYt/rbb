<template>
    <div class="plane">
        <div class="plane__left">
            <h1>TTS & STT tizimlarini o'rnatish reja qilingan sohalar</h1>
        </div>
        <div class="plane__right">
            <div class="right__cards">
                <div class="right__card" data-aos="fade-up">
                    <img src="https://i.postimg.cc/Yqwqm9WY/robot-1.png" alt="">
                    <p>IOT & Robotech</p>
                </div>
                <div class="right__card" data-aos="fade-up">
                    <img src="https://i.postimg.cc/fb2Wpfkh/marketing-15.png" alt="">
                    <p>Media & Xizmatlar</p>
                </div>
                <div class="right__card" data-aos="fade-up">
                    <img src="https://i.postimg.cc/Vs9pNLBJ/Group-2.png" alt="">
                    <p>Smart Yordamchilar</p>
                </div>
                <div class="right__card" data-aos="fade-up">
                    <img src="https://i.postimg.cc/59P5ghfP/scholarship-1.png" alt="">
                    <p>Ta’lim Sohalari</p>
                </div>
                <div class="right__card" data-aos="fade-up">
                    <img src="https://i.postimg.cc/9MD9nMmJ/smartphone.png" alt="">
                    <p>Online Dasturlar</p>
                </div>
                <div class="right__card" data-aos="fade-up">
                    <img src="https://i.postimg.cc/CMj5LDQb/languages.png" alt="">
                    <p>Ovozli Tarjimonlar sohalari</p>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style scoped>
.plane {
    display: flex;
    justify-content: space-between;
    width: 100%;
    height: 240px;
    background-color: #F4F4F4;
    padding: 10px;
    border-radius: 10px;
    margin-top: 50px;
}

.plane__left {
    background-color: #51CCF3;
    flex: 3;
    padding: 10px 20px;
    border-radius: 20px;
}

.plane__left h1 {
    font-weight: 500;
    font-size: 32px;
    line-height: 39px;
    color: #FFFFFF;
}

.plane__right {
    flex: 6;
}

.right__cards {
    display: flex;
    flex-wrap: wrap;
    padding: 10px;
    justify-content: space-between;
    margin-top: 20px;
}

.right__card {
    display: flex;
    gap: 10px;
    align-items: center;
    font-size: 18px;
    width: 130px;
    margin: 0px 40px;
}
</style>