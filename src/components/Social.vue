<template>
    <div class="social">
        <div class="social__left">
            <h1>Telegram kanalimizga
                <span>obuna bo‘ling</span>
                va yangiliklarimizdan doimiy xabardor bo‘lib boring
            </h1>
            <img src="https://i.postimg.cc/br093WJg/LABEL-TELEGRAM-TALK-1.png" alt="">
        </div>
        <div class="social__right">
            <img src="https://i.postimg.cc/pV0TnkqM/i-Phone-12-Pro-1.png" alt="">
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style scoped>
.social {
    margin-top: 50px;
    background: url("https://i.postimg.cc/gkwVTxTQ/image-1212-1.png");
    display: flex;
    background-color: #0077b6;
    align-items: center;
    justify-content: space-between;
    border-radius: 50px;
    padding: 10px;
    position: relative;
}

.social__left {
    display: flex;
    flex-direction: column;
}

.social__left h1 {
    margin: 20px 40px;
    font-weight: 300;
    font-size: 36px;
    line-height: 54px;
    color: #ffffff;
    width: 630px;
}

.social__left h1>span {
    font-weight: 800;
    font-size: 42px;
    line-height: 60px;
}

.social__left img {
    width: 440px;
}

.social__right img {
    position: absolute;
    bottom: 0px;
    right: 110px;
}
</style>