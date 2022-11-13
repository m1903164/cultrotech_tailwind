<template>
    <nav>
        <div class="container m-auto pt-7 pb-5 flex flex-wrap max-w-7xl">
            <a href="#" class="mr-10 pt-0">
                <img src="../assets/logo.svg">
            </a>
            <div class="flex flex-col justify-between">
                <ul class="flex pt-3 gap-5">
                    <li>О компании</li>
                    <li>Новости</li>
                    <li>Галерея</li>
                    <li>Доставкаи оплата</li>
                    <li>Контакты</li>
                    <li>Партнеры</li>
                </ul>
                <div class="flex mb-4 justify-between">
                    <form >
                        <input class="search__input" type="text" placeholder="Искать здесь...">
                    </form>
                    <a class="flex">
                        <img class="mr-2" src="../assets/mail.svg">
                        <p style="color:white">Cultrotech_order@mail.ru</p>
                    </a>
                </div>
            </div>
        </div>
    </nav>
</template>

<style scoped>
nav {
    background-color: #150C07;
}

ul {
    color: #C9A378;
    font-weight: 500;
    font-size: 0.75em;
}
</style>