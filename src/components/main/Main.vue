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
                                <div class="slide">
                                    <img src="@/assets/img/range.svg" alt="">
                                    <img src="@/assets/img/roundm.svg" alt="" class="slide__round">
                                </div>
                            </div>
                            <div class="main__earn-content-btn-range">
                                <div class="main__earn-content-btn-range-top">
                                    <p>Срок инвестирования</p>
                                    <output>24 месяца</output>
                                </div>
                                <div class="second-slide">
                                    <img src="@/assets/img/range.svg" alt="">
                                    <img src="@/assets/img/roundm.svg" alt="" class="second-round">
                                </div>
                            </div>
                            <div class="main__earn-content-btn-check">
                                <p>Порядок выплаты дохода</p>
                                <div class="main__earn-content-btn-check-block">
                                    <button class="active">
                                        <input type="checkbox" name="invest" checked id="all">
                                        <label for="all">Ежемесячно</label>
                                    </button>
                                    <button>
                                        <input type="checkbox" name="invest" id="last">
                                        <label for="last">В конце срока</label>
                                    </button>
                                </div>
                            </div>
                            <div class="main__earn-content-btn-range">
                                <div class="main__earn-content-btn-range-top">
                                    <p>Пополнение вклада</p>
                                    <output>30 000 ₽ <span>/в месяц</span></output>
                                </div>
                                <div class="third-slide">
                                    <img src="@/assets/img/range.svg" alt="">
                                    <img src="@/assets/img/roundm.svg" alt="" class="third-round">
                                </div>
                            </div>
                        </div>
                        <div class="main__earn-content-btn-center">
                            <img src="@/assets/img/Frame.png" alt="">
                            <img src="@/assets/img/round.svg" alt="" class="main__earn-content-btn-center-img">
                            <img src="@/assets/img/round.svg" alt="" class="main__earn-content-btn-center-img">
                            <img src="@/assets/img/round.svg" alt="" class="main__earn-content-btn-center-img">
                            <img src="@/assets/img/round.svg" alt="" class="main__earn-content-btn-center-img">
                            <img src="@/assets/img/round.svg" alt="" class="main__earn-content-btn-center-img">
                            <img src="@/assets/img/round.svg" alt="" class="main__earn-content-btn-center-img">
                            <img src="@/assets/img/stick.svg" alt="" class="main__earn-content-btn-center-stc">
                            <img src="@/assets/img/stick.svg" alt="" class="main__earn-content-btn-center-stc">
                            <img src="@/assets/img/stick.svg" alt="" class="main__earn-content-btn-center-stc">
                            <img src="@/assets/img/stick.svg" alt="" class="main__earn-content-btn-center-stc">
                        </div>
                        <div class="main__earn-content-btn-right">
                            <div class="main__earn-content-btn-right-media">
                                <div class="main__earn-content-btn-right-per">
                                    <output>12,5%</output>
                                    <span>Доходность</span>
                                </div>
                                <div class="main__earn-content-btn-right-per">
                                    <output>282 366 ₽</output>
                                    <span>Сумма доходности</span>
                                </div>
                            </div>
                            <div class="main__earn-content-btn-right-per perdist">
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

        <section class="main__resume">
            <div class="main__resume-content">
                <div class="main__resume-content-lft">
                    <div class="main__resume-content-lft-top">
                        <img src="@/assets/img/resume.png" alt="">
                    </div>
                    <button>
                        Видео о работе компании
                        <img src="@/assets/img/PlayCircle.svg" alt="">
                    </button>
                </div>
                <div class="main__resume-content-rgt">
                    <h3>Разумные инвестиции</h3>
                    <span>Вкладывая свои деньги в ИФК «Нур Финанс», инвестор получает:</span>
                    <div class="main__resume-content-rgt-num">
                        <img src="@/assets/img/1.png" alt="">
                        <p>Долю в имуществе и активах компании</p>
                    </div>
                    <div class="main__resume-content-rgt-num second-num">
                        <img src="@/assets/img/2.png" alt="">
                        <p>Долю в прибыли компании</p>
                    </div>
                    <p class="main__resume-content-rgt-p">От торговых операций, обеспеченных реальными активами.
                        Доля в прибыли инвестора закрепляется в договоре в соответствии с условиями, которые зависят от
                        суммы и срока инвестиционного вклада. В случае отрицательного финансового результата, убытки
                        распределяются между инвесторами пропорционально доле каждого инвестора (вкладчика)
                        в общем капитале компании.</p>
                </div>
            </div>
        </section>

    </main>
</template>
