<script setup>

</script>

<template>
    <main class="main">
        <div class="container">
            <div class="main__content-cards">
                <div class="main__content-cards-card">
                    <div class="main__content-cards-block">
                        <img src="@/assets/img/leaf.svg" alt="">
                        <img src="@/assets/img/Coin.svg" alt="">
                    </div>
                    <p>Накапливайте, принося пользу обществу</p>
                </div>
                <div class="main__content-cards-card">
                    <div class="main__content-cards-block">
                        <img src="@/assets/img/leaf.svg" alt="">
                        <img src="@/assets/img/Wallet.svg" alt="">
                    </div>
                    <p>Зарабатывайте честно и справедливо</p>
                </div>
                <div class="main__content-cards-card">
                    <div class="main__content-cards-block">
                        <img src="@/assets/img/leaf.svg" alt="">
                        <img src="@/assets/img/Chart.svg" alt="">
                    </div>
                    <p>Вкладывайте в реальные проверенные сделки</p>
                </div>
                <div class="main__content-cards-card">
                    <div class="main__content-cards-block">
                        <img src="@/assets/img/leaf.svg" alt="">
                        <img src="@/assets/img/safe.svg" alt="">
                    </div>
                    <p>Обеспечьте вложения надежными активами</p>
                </div>
            </div>
        </div>

        <section class="main__earn">
            <div class="container">
                <div class="main__earn-content">
                    <h2>Рассчитай свои накопления и доход</h2>
                    <div class="main__earn-content-btn">
                        <div class="main__earn-content-btn-lft">
                            <div class="main__earn-content-btn-range">
                                <div class="main__earn-content-btn-range-top">
                                    <p>Сумма вклада</p>
                                    <output>1 000 000 ₽</output>
                                </div>
                                <input type="range">
                            </div>
                            <div class="main__earn-content-btn-range">
                                <div class="main__earn-content-btn-range-top">
                                    <p>Сумма вклада</p>
                                    <output>1 000 000 ₽</output>
                                </div>
                                <input type="range">
                            </div>
                            <div class="main__earn-content-btn-check">
                                <p>Порядок выплаты дохода</p>
                                <div class="main__earn-content-btn-check-block">
                                    <button>
                                        <input type="checkbox">
                                        <span>Ежемесячно</span>
                                    </button>
                                    <button>
                                        <input type="checkbox">
                                        <span>Ежемесячно</span>
                                    </button>
                                </div>
                            </div>
                            <div class="main__earn-content-btn-range">
                                <div class="main__earn-content-btn-range-top">
                                    <p>Сумма вклада</p>
                                    <output>1 000 000 ₽</output>
                                </div>
                                <input type="range">
                            </div>
                        </div>
                        <div class="main__earn-content-btn-center">
                            <img src="@/assets/img/Frame.png" alt="">
                        </div>
                        <div class="main__earn-content-btn-right">
                            <div class="main__earn-content-btn-right-top">
                                <div class="main__earn-content-btn-right-per">
                                    <output>12,5%</output>
                                    <span>Доходность</span>
                                </div>
                                <div class="main__earn-content-btn-right-per">
                                    <output>282 366 ₽</output>
                                    <span>Сумма доходности</span>
                                </div>
                            </div>
                            <div class="main__earn-content-btn-right-center">
                                <output>1 282 366 ₽</output>
                                <span>Итоговая сумма</span>
                            </div>
                            <button>
                                Инвестировать
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>
</template>
