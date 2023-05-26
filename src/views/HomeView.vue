<template>
    <img src="../assets/image/logo.svg" class = "logo" alt="logo" >
    <div class = "top-menu">
    <a href="">
        ВСЕ ТОВАРЫ
    </a>
    <a href="">
        КАТЕГОРИИ
    </a>
    <a href="">
        О НАС
    </a>
    <a href="">
        ПОДДЕРЖКА
    </a>
    <img src="../assets/image/loupe.svg" alt="loupe" class="img-header">
    <img src="../assets/image/basket.svg" alt="basket">
    </div>
    <div class="nav">
        <img src="../assets/image/strelk1.svg">
    <div class="top-nav">
        <div class="square">
            <div class="text-square">
            <h1 class="h1">Новые смартфоны</h1>
            <p>Описание Описание Описание Описание Описание Описание</p>
            <button class="round">Посмотреть</button>
            <div class="line">
                <hr><hr><hr>
            </div>
            </div>
            <img src="../assets/image/top-phone.png" class="top-phone" alt="top-phone" >
        </div>
    </div>
        <img src="../assets/image/strelk2.svg">
    </div>
    <h2>Категории</h2>
    <div class="categories">
        <div class="flex1">
            <div class="rectangle">
                <img src="../assets/image/notebook.png" alt="notebook">
                <h4 class="text-rec">Ноутбуки</h4>
            </div>
            <div>
                <img src="../assets/image/smartwatch3.png" alt="notebook">
                <h4>Смарт-
                    <br>часы</h4>
            </div>
        </div>
        <div class="flex2">
            <div>
                <img src="../assets/image/smartphones.png" alt="notebook">
                <h4>Cмартфоны</h4>
            </div>
        </div>
        <div class="flex3">
            <div>
                <h4>Планшеты</h4>
                <img src="../assets/image/tablet.png" alt="notebook">
            </div>
        </div>
    </div>
    <h2>Популярное</h2>
    <div class="popular">
        <div class="prod-item">
            <img src="../assets/image/macpro.png" alt="macpro">
            <p class="p-popular">MacBook Pro 13</p>
            <p>Описание Описание Описание Описание Описание</p>
            <span class="old">$ 1,200.00 USD</span>
        </div>
        <div class="prod-item">
            <img src="../assets/image/smartwatch.png" alt="smartwatch">
            <p class="p-popular">Smart Galaxy Watch 3</p>
            <p>Описание Описание Описание Описание Описание</p>
            <span class="old">$ 1,200.00 USD</span>
        </div>
        <div class="prod-item">
            <img src="../assets/image/macm1.png" alt="macm1">
            <p class="p-popular">MacBook Air M1</p>
            <p>Описание Описание Описание Описание Описание</p>
            <span class="old">$ 1,200.00 USD</span>
        </div>
        <div class="prod-item">
            <img src="../assets/image/ipad.png" alt="ipad">
            <p class="p-popular">iPad 512GB 2023</p>
            <p>Описание Описание Описание Описание Описание</p>
            <span class="old">$ 1,200.00 USD</span>
        </div>
    </div>
    <h2>Подборки товаров</h2>
    <div class="selections">
        <div class="sel-item">
            <div class="text-cel">
            <h3>Лучшие смарт-часы</h3>
            <button class="round-button">Посмотреть</button>
            </div>
            <img src="../assets/image/smartwatch2.png" alt="smartwatch2">
        </div>
        <div class="sel-item">
            <div class="text-cel">
            <h3>Лучшие смарт-часы</h3>
            <button class="round-button">Посмотреть</button>
            </div>
            <img src="../assets/image/technique.png" alt="technique">
        </div>
        <div class="sel-item">
            <div class="text-cel">
            <h3>Лучшие смарт-часы</h3>
            <button class="round-button">Посмотреть</button>
            </div>
            <img src="../assets/image/technique2.png" alt="technique2">
        </div>
    </div>
    <h2>Что-то ищете?</h2>
    <div class="search-container">
        <div class="search-head">
        <input type="text" placeholder="Введите запрос" class="search-input">
        </div>
        <div class="search-button">
        <button class="round-button2">iPhone</button>
        <button class="round-button2">Зарядка</button>
        <button class="round-button2">Xiaomi</button>
        <button class="round-button2">Google Pixel 4</button>
        <button class="round-button2">Ноутбук</button>
        </div>
    </div>
    <div class="promotion">
        <h2>Не упустите ничего</h2>
        <p>Подпишитесь на наши обновления, чтобы получать уведомления о лучших предложениях и скидках.</p>
        <img src="../assets/image/promotion.png" alt="promotion">
        <form>
            <input class="email" type="email" placeholder="Ваша почта">
            <button class="round-button3">Отправить</button>
        </form>
    </div>

    <footer>
        <img src="../assets/image/logo.svg" class = "logo" alt="logo" >
        <div class="flex-container width">
            <div class="menu-footer col">
                <div class="col-menu">
                    <a href = "" class="name">Все товары</a>
                    <a href = "" >Смартфоны</a>
                    <a href = "" >Смарт-часы</a>
                    <a href = "" >Планшеты</a>
                    <a href = "" >Ноутбуки</a>
                </div>
                <div class="col-menu">
                    <a href = "" class="name">Компания</a>
                    <a href = "" >О нас</a>
                    <a href = "" >Поддежка</a>
                </div>
                <div class="col-menu">
                    <a href = "" class="name">Поддержка</a>
                    <a href = "" >Контакты</a>
                </div>
            </div>
            </div>
    </footer>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
}
</script>