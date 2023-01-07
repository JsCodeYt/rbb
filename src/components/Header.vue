<template>
    <header class="header" id="header">
        <div class="line">
        </div>
        <div class="line__right"></div>
        <div class="header__left">
            <h1>Matnni ovozga o'girish</h1>
            <div class="title_line"></div>
            <p>
                21-oktabr, O'zbek tiliga davlat tili maqomi berilganligining 31 yillik munosabati bilan o'zbekcha matnni
                nutqga o'girish texnologiyasini ishlab chiqdik
            </p>
            <div class="left__cards">
                <div class="left__card">
                    <img src="https://i.postimg.cc/LXRLqN09/Vector-3.png" alt="">
                    <span>Tabiiy ovozda</span>
                </div>
                <div class="left__card">
                    <img src="https://i.postimg.cc/0yRQ2r4x/Shape-68.png" alt="">
                    <span>To'liq sun'iy intelekt asosida</span>
                </div>
                <div class="left__card">
                    <img src="https://i.postimg.cc/k4pSjqg4/deadline.png" alt="">
                    <span>Yuqori tezlik</span>
                </div>
                <div class="left__card">
                    <img src="https://i.postimg.cc/vZZVd4xB/voice.png" alt="">
                    <span>2ta ovozda tinglash imkoniyati</span>
                </div>
            </div>
        </div>
        <div class="header__right">
            <img src="https://i.postimg.cc/j5h2Bvj1/198-1.png" alt="">
        </div>
    </header>
</template>
<script>
export default {

}
</script>
<style>
#header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-top: 20px;
    font-family: 'Outfit';
}

.line {
    position: absolute;
    width: 5px;
    height: 64px;
    left: 718px;
    top: 111px;
    background-color: #51CCF3;
}

.line__right {
    position: absolute;
    width: 5px;
    height: 64px;
    left: 1317px;
    top: 233px;
    background: #51CCF3;
}

.header__left>h1 {
    font-style: normal;
    font-weight: 700;
    font-size: 56px;
    line-height: 60px;
}

.header__right img {
    width: 600px;
}

.title_line {
    position: absolute;
    width: 5px;
    height: 61px;
    left: 400px;
    top: 280px;
    background: #51CCF3;
}

.header__left>p {
    font-family: 'Outfit';
    font-style: normal;
    font-weight: 300;
    font-size: 20px;
    line-height: 39px;
    color: #170F49;
    width: 517px;
}

.left__cards {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    width: 500px;
}

.left__card {
    font-size: 15px;
    display: flex;
    align-items: center;
    cursor: pointer;
    margin-right: 40px;
    margin-top: 10px;
    gap: 15px;
}

.left__card img {
    transition: all 0.5s ease-in-out;
}

.left__card:hover img {
    transform: rotate(360deg);
}
</style>