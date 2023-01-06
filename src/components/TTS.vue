<template>
    <div class="tts__header">
        <h1 class="tts__title">
            TTS.uz API xizmatidan foydalanish ketma-ketligi
        </h1>
    </div>
    <div class="tts">
        <div class="tts-map__cards" data-aos="fade-left">
            <div class="card">
                <img src="https://i.postimg.cc/xdv0tPQ5/notebook.png" alt="">
                <h4>Shartnoma</h4>
                <p>tts.uz API xizmatidan foydalanish uchun shartnoma qilinadi</p>
            </div>
            <div class="card">
                <img src="https://i.postimg.cc/pdvNXhh1/Budget.png" alt="">
                <h4>Tariflar & To'lovlar</h4>
                <p>Shartnoma qilinganidan so'ng ta’rif tanlanadi</p>
            </div>
            <div class="card">
                <img src="https://i.postimg.cc/sDSsjRHx/rocket.png" alt="">
                <h4>O'rnatish & Ishga tushirish</h4>
                <p>Saytga o'rnatish uchun JavaScript plugin beriladi va ungan api token biriktirilib saytga o'rnatiladi
                </p>
            </div>
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style scoped>
.tts__header {
    display: flex;
    justify-content: center;
}

.tts__title {
    text-align: center;
    font-weight: 700;
    font-size: 42px;
    line-height: 60px;
    text-align: center;
    color: #170F49;
    width: 514px;
}

.tts-map__cards {
    display: flex;
    justify-content: space-between;
}

.card {
    width: 30%;
    padding: 10px;
    text-align: center;
    transition: all 0.5s ease-in-out;
}

.card:hover {
    -webkit-box-shadow: -1px -3px 40px 0px rgba(34, 60, 80, 0.2);
    -moz-box-shadow: -1px -3px 40px 0px rgba(34, 60, 80, 0.2);
    box-shadow: -1px -3px 40px 0px rgba(34, 60, 80, 0.2);
}

.card img {
    transition: all .5s ease-in-out;
}

.card:hover img {
    transform: scale(1.9);
}

.card h4 {
    color: #170F49;
}

.card p {
    font-size: 12px;
    font-weight: 200;
    color: #170F49;
}
</style>