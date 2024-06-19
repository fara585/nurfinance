<script setup>
import { ref } from 'vue';
const lang = ref(true);
const activebtn = ref("cabinet");
const activeradio = ref("online");
const setActive = (value) => {
    activeradio.value = value;
};
</script>

<template>
    <header class="header">
        <div class="container">
            <div class="header__content">
                <h3>Инвестиционно-финансовая компания</h3>
                <ul class="header__content-list">
                    <li>
                        <img src="@/assets/img/navloc.svg" alt="">
                        <a href="#abc" class="header__content-list-items">Город Казань</a>
                    </li>
                    <li><a href="#abc" class="header__content-list-items">О компании</a></li>
                    <li><a href="#abc" class="header__content-list-items">Отзывы</a></li>
                    <li><a href="#abc" class="header__content-list-items">Халяль подробно</a></li>
                    <li><a href="#abc" class="header__content-list-items">Отчетность</a></li>
                    <li><a href="#abc" class="header__content-list-items">Наши партнеры</a></li>
                    <li><a href="#abc" class="header__content-list-items">Сотрудничество</a></li>
                    <li>
                        <a href="#abc" class="header__content-list-items">Контакты</a>
                        <img src="@/assets/img/navmap.svg" alt="">
                    </li>
                </ul>
                <button @click="lang = !lang">
                    {{ lang ? " RU " : "EN" }}
                </button>
            </div>
        </div>
        <nav class="nav">
            <div class="container">
                <div class="nav__content">
                    <img src="@/assets/img/headerlogo.png" alt="">
                    <ul class="nav__content-list">
                        <li><a href="#abc" class="nav__content-list-items">Инвестиции</a></li>
                        <li><a href="#abc" class="nav__content-list-items">Рассрочка</a></li>
                        <li><a href="#abc" class="nav__content-list-items">Калькулятор</a></li>
                    </ul>
                    <div class="nav__content-phone">
                        <img src="@/assets/img/Phone.svg" alt="">
                        <a href="tel:8 800 2700 700">8 800 2700 700</a>
                    </div>
                    <img src="@/assets/img/lupa.svg" alt="">
                    <div class="nav__content-btns">
                        <button :class="{ 'active': activebtn === 'cabinet' }" @click="activebtn = 'cabinet'">
                            Личный Кабинет
                        </button>
                        <button :class="{ 'active': activebtn === 'online' }" @click="activebtn = 'online'">
                            Онлайн-заявка
                        </button>
                    </div>
                </div>
            </div>
        </nav>
        <section class="section">
            <div class="container">
                <div class="section__content">
                    <div class="section__content-lft">
                        <div class="section__content-top">
                            <a href="#abc">главная</a>
                            <img src="@/assets/img/mainlft.svg" alt="">
                            <a href="#abc">инвестиции</a>
                        </div>
                        <h1>Максимальная доля прибыли по вкладам <span>НурФинанс</span></h1>
                        <p>Инвестор получает наибольший капитализированный доход</p>
                        <div class="section__content-bottom">
                            <button>
                                Инвестиционные продукты
                            </button>
                            <div class="section__content-bottom-radios">
                                <span :class="{ 'active': activeradio === 'online2' }"
                                    @click="setActive('online2')"></span>
                                <span :class="{ 'active': activeradio === 'radio' }" @click="setActive('radio')"></span>
                                <span :class="{ 'active': activeradio === 'online' }"
                                    @click="setActive('online')"></span>
                                <span :class="{ 'active': activeradio === 'online3' }"
                                    @click="setActive('online3')"></span>
                                <span :class="{ 'active': activeradio === 'online4' }"
                                    @click="setActive('online4')"></span>
                            </div>
                        </div>
                    </div>
                    <img src="@/assets/img/headercenter.png" alt="" class="section__content-center">
                    <div class="section__content-right">
                        <button>
                            <img src="@/assets/img/headerseclft.svg" alt="">
                        </button>
                        <button>
                            <img src="@/assets/img/headersecrught.svg" alt="">
                        </button>
                    </div>
                </div>
            </div>
        </section>
    </header>
</template>