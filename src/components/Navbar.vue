<template>
    <div class="navbar">
        <div class="navbar__left">
            <img src="https://i.postimg.cc/bvxbmyHq/Group.png" alt="Group">
        </div>
        <div class="navbar__right">
            <ul class="right__items">
                <li class="right__item">Bosh sahhifa</li>
                <li class="right__item">Loyihalar</li>
                <li class="right__item">API</li>
                <li class="right__item">Sohalar</li>
                <li class="right__item">Statistika</li>
            </ul>
            <button class="navbar__button">Kirish</button>
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style scoped>
.navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-family: "Sora";
}

.navbar__left img {
    width: 100px;
}

.navbar__right {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 1rem;
}

.right__items {
    display: flex;
    align-items: center;
    gap: 3rem;
    list-style: none;
}

.right__item {
    font-size: 16px;
    cursor: pointer;
    position: relative;
}

.right__item::after {
    content: "";
    height: 3px;
    width: 0%;
    background-color: #F92B74;
    position: absolute;
    left: 0;
    bottom: -7px;
    transition: all 0.5s ease-in-out;
}

.right__item:hover::after {
    width: 50%;
}

.navbar__button {
    border: 1px solid #F92B74;
    padding: 15px 40px;
    font-size: 14px;
    border-radius: 50px;
    color: #F92B74;
    cursor: pointer;
    background-color: #fff;
    transition: all 0.2s ease-in-out;
}

.navbar__button:hover {
    background-color: #F92B74;
    color: #fff;
}
</style>