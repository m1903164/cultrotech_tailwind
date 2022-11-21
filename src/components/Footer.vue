<template>
    <footer class="site-footer">
        <div class="logo">
            <a>
                <img class="f-logo" src="../assets/footer-logo.svg">
            </a>
        </div>
        <div class="w-full max-w-7xl m-auto">
            <ul class="flex justify-between mb-10 mr-0">
                <li class="mr-10">О компании</li>
                <li class="mr-10">Новости</li>
                <li class="mr-10">Галерея</li>
                <li class="mr-10">Доставка и оплата</li>
                <li class="mr-10">Контакты</li>
                <li>Партнеры</li>
            </ul>
            <div class="text-white flex justify-between">
                <div>
                    <a class=" mb-5 flex" href="">
                        <img class="mr-1" src="../assets/mail.svg">
                        <p> Cultrotech_order@mail.ru</p>
                    </a>
                    <div class="flex">
                        <a href="" class="mr-6">
                            <img src="../assets/f-vk.svg" alt="">
                        </a>
                        <a href="" class="mr-6">
                            <img src="../assets/f-inst.svg" alt="">
                        </a>
                        <a href="">
                            <img src="../assets/f-fb.svg" alt="">
                        </a>
                    </div>
                </div>
                <div>
                    <a class="mb-5" href="https://cultrotech.org/privacy-policy/">
                        Политика конфиденциальности
                    </a>
                    <p>
                        2020 все права защищены
                    </p>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>

</script>

<style scoped>
.site-footer {
    background: #150C07;
    text-align: center;
    padding-bottom: 80px;
}

.logo {
    padding-top: 18px;
    position: relative;
    display: inline-block;
    margin-right: 0;
    margin-bottom: 20px;
}

.logo::before {
    content: '';
    width: 270px;
    opacity: 0.5;
    border: 1px solid #FFFFFF;
    position: absolute;
    top: 55%;
    left: -338px;
}

.logo::after {
    content: '';
    width: 270px;
    opacity: 0.5;
    border: 1px solid #FFFFFF;
    position: absolute;
    bottom: 43.5%;
    right: -338px;
}

.f-logo {
    width: 98px;
    height: 116px;
    margin-bottom: 2px;
}

ul {
    color: #C9A378;
    font-family: Gilroy;
    font-size: 1em;
    text-transform: none !important;
}
</style>