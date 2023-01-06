<template>
    <div class="box">
        <footer>
            <div class="footer__left">
                <img src="https://i.postimg.cc/MKXWfFZ2/Group-3.png" alt="">
                <p>Ovoz va Ovoz atrofidagi loyihalar ustida ish olib boramiz</p>
                <div class="networks">
                    <i class="fa-brands fa-telegram"></i>
                    <i class="fa-brands fa-square-instagram"></i>
                    <i class="fa-brands fa-facebook"></i>
                    <i class="fa-brands fa-linkedin"></i>
                </div>
            </div>
            <div class="footer__center">
                <ul class="center__left">
                    <span>Foydali havolalar</span>
                    <div class="nav">
                        <li class="left__item">Features</li>
                        <li class="left__item">Pravicy and Policy</li>
                        <li class="left__item">Case studies</li>
                        <li class="left__item">Reviews</li>
                        <li class="left__item">Updates</li>
                    </div>
                </ul>
                <ul class="center__right">
                    <span>Contacts us</span>
                    <div class="nav">
                        <li class="right__item">
                            <i class="fa-solid fa-envelope"></i>
                            <span>contact@tts.uz</span>
                        </li>
                        <li class="right__item">
                            <i class="fa-solid fa-phone"></i>
                            <span>+998(99) 033 73 67</span>
                        </li>
                        <li class="right__item">
                            <i class="fas fa-location"></i>
                            <span>794 Mcallister St San Francisco, 94102</span>
                        </li>
                    </div>
                </ul>
            </div>
            <div class="footer__right">
                <h1>
                    Facebook
                </h1>
                <img src="https://i.postimg.cc/J7YQQs8D/image-1213.png" alt="">
            </div>
        </footer>
        <div class="footer-end">
            <hr>
            <div class="footer-end__start">
                <p>All Rights are Reserved © 2022 TTS.uz</p>
                <p>Created by Quantic</p>
            </div>
        </div>
    </div>
</template>
<style scoped>
.box {
    background-color: #170F49;
    padding: 50px 100px;
}

footer {
    display: flex;
    padding: 20px;
    justify-content: space-between;
    gap: 10px;
}

.footer__left p {
    color: #FFFFFF;
    font-size: 13px;
    width: 300px;
    margin-top: 10px;
}

.networks {
    display: flex;
    align-items: center;
    gap: 15px;
    font-size: 30px;
    margin-top: 40px;
}

.networks i {
    transition: all 0.5s ease-in-out;
    cursor: pointer;
}

.networks>i:hover {
    color: white;
    transform: translateY(-30px);
}

.footer__center {
    display: flex;
    justify-content: space-between;
    gap: 1rem;
}

.center__left {
    list-style: none;
}

.center__left span {
    color: #FFFFFF;
    font-size: 16px;
}

.left__item {
    color: rgba(255, 255, 255, 0.6);
    font-weight: 300;
    font-size: 18px;
    line-height: 20px;
    margin: 10px 0px;
}

.nav {
    margin-top: 30px;
}

.center__right {
    list-style: none;
}

.center__right span {
    font-size: 16px;
    color: #FFFFFF;
}

.right__item span {
    color: rgba(255, 255, 255, 0.6);
    font-size: 12px;
}

.right__item {
    display: flex;
    align-items: center;
    gap: 10px;
    margin: 10px 0px;
}

.footer__right {
    color: #FFFFFF;
    font-size: 12px;
    display: flex;
    flex-direction: column;
    gap: 2rem;
}
.footer-end__start {
    display: flex;
    justify-content: space-between;
    color: #FFFFFF;
    margin-top: 10px;
    font-size: 14px;
}
</style>