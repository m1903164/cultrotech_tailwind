<template>
    <div class="main-product">
        <div class="container m-auto max-w-7xl">
            <h2 class="mb-10">
                Наши проекты
            </h2>
            <div>
                <ul class="flex gap-7">
                    <li>
                        <h2 class="product-title">Название продукта</h2>
                        <div class="image"></div>
                    </li>
                    <li>
                        <h2 class="product-title">Название продукта</h2>
                        <div class="image"></div>
                    </li>
                    <li>
                        <h2 class="product-title">Название продукта</h2>
                        <div class="image"></div>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .main-product {
        margin-bottom: 55px;
    }

    h2 {
        font-family: Charlemagne;
        font-size: 2.25em;
        color: #3E312A;
        text-align: center;
    }

    .product-title {
        text-transform: capitalize !important;
        font-family: Gilroy !important;
        font-style: normal !important;
        font-weight: normal !important;
        font-size: 24px !important;
        color: #000000 !important;
        text-align: left !important;
    }

    .image {
        width: 370px;
        height: 246px;
        background-color:#3E312A;
    }
</style>