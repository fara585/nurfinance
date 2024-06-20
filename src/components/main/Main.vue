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

        <section class="main__graph">
            <div class="main__graph-content-top">
                <div class="main__graph-content-top-lft">
                    <h3>Доходность</h3>
                    <p>Доходность портфеля компании и инвестиционных вкладов «Нурфинанс» в % годовых за последние 11
                        месяцев</p>
                </div>
                <div class="main__graph-content-top-rgt">
                    <div class="main__graph-content-top-rgt-block">
                        <img src="../../assets/img/graph.svg" alt="">
                        <span>Общая доходность</span>
                    </div>
                    <div class="main__graph-content-top-rgt-block">
                        <img src="../../assets/img/grapg2.svg" alt="">
                        <span>Средняя доходность инвесторов</span>
                    </div>
                </div>
            </div>
        </section>

        <section class="main__graph-sec">
            <span class="grf pos1"></span>
            <span class="grf pos2"></span>
            <span class="grf pos3"></span>
            <span class="grf pos4"></span>
            <span class="grf pos5"></span>
            <span class="grf pos6"></span>
            <span class="grf pos7"></span>
            <span class="grf pos8"></span>
            <span class="grf pos9"></span>
            <span class="grf pos10"></span>
            <span class="round r1"></span>
            <span class="round r2"></span>
            <span class="round r3"></span>
            <span class="round r4"></span>
            <span class="round r5"></span>
            <span class="round r6"></span>
            <span class="round r7"></span>
            <span class="round r8"></span>
            <span class="round r9"></span>
            <span class="round r10"></span>
            <span class="round r11"></span>
            <span class="stick"></span>
            <span class="stick two"></span>
            <span class="stick thre"></span>
            <span class="stick four"></span>
            <span class="stick five"></span>
            <span class="stick six"></span>
            <span class="stick sev"></span>
            <span class="stick eig"></span>
            <span class="stick nine"></span>
            <span class="stick ten"></span>
            <span class="stick elv"></span>
            <span class="perc per1">32,53%</span>
            <span class="perc per2">38,42%</span>
            <span class="perc per3">28,89%</span>
            <span class="perc per4">27,66%</span>
            <span class="perc per5">26,64%</span>
            <span class="perc per6">27,60%</span>
            <span class="perc per7">26,76%</span>
            <span class="perc per8">29,88%</span>
            <span class="perc per9">25,23%</span>
            <span class="perc per10">25,20%</span>
            <span class="perc per11">25,84%</span>
            <span class="grp grp1"></span>
            <span class="grp grp2"></span>
            <span class="grp grp3"></span>
            <span class="grp grp4"></span>
            <span class="grp grp5"></span>
            <span class="grp grp6"></span>
            <span class="grp grp7"></span>
            <span class="grp grp8"></span>
            <span class="grp grp9"></span>
            <span class="grp grp10"></span>

            <span class="rnd d1"></span>
            <span class="rnd d2"></span>
            <span class="rnd d3"></span>
            <span class="rnd d4"></span>
            <span class="rnd d5"></span>
            <span class="rnd d6"></span>
            <span class="rnd d7"></span>
            <span class="rnd d8"></span>
            <span class="rnd d9"></span>
            <span class="rnd d10"></span>
            <span class="rnd d11"></span>

            <div class="main__graph-sec-date">
                <output>Сентябрь 2020</output>
                <output>Октябрь <br> 2020</output>
                <output>Ноябрь <br> 2020</output>
                <output>Декабрь <br> 2020</output>
                <output>Январь <br> 2021</output>
                <output>Февраль 2021</output>
                <output>Март <br> 2021</output>
                <output>Апрель <br> 2021</output>
                <output>Май <br> 2021</output>
                <output>Июнь <br> 2021</output>
                <output>Июль <br> 2021</output>
            </div>

        </section>

        <section class="main__info">
            <div class="container">
                <div class="main__info-content">
                    <div class="main__info-content-left">
                        <h1>Инвестиционные продукты</h1>
                        <p>
                            ИФК «Нурфинанс» готов принимать инвестиции в сумме от 100 000 рублей сроком от 3-х месяцев
                            до 3-х лет на следующих
                            условиях:
                        </p>
                    </div>
                    <div class="main__info-content-right">
                        <p>
                            Вкладчик (инвестор) вносит денежные средства в капитал Товарищества на вере «Нурфинанс»,
                            становясь участником Товарищества
                            на вере, неся риск убытков, связанных с деятельностью Товарищества, в пределах внесенного
                            вклада, но при этом не принимает
                            участие в осуществлении Товариществом предпринимательской деятельности. Такая форма участия
                            инвестора основана на
                            Шариатском стандарте «Мудараба». По договору, клиент-инвестор передает в управление свой
                            капитал компании «Нур Финанс».
                            Далее капитал направляются на финансирование торговых операций и бизнес-проектов. Начисление
                            дохода, причитающегося к
                            выплате Вкладчику (инвестору), осуществляется Товариществом ежемесячно.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <section class="main__user">
            <div class="container">
                <div class="main__user-content">
                    <div class="main__user-content-card">
                        <img src="@/assets/img/man1.png" alt="" />

                        <div class="main__user-content-card-shadow"></div>
                        <div class="main__user-content-card-bottom">
                            <p class="main__user-content-card-invest">Инвестиции</p>
                            <h3>Вклад Накопительный</h3>

                            <div class="main__user-content-card-nums">
                                <div class="main__user-content-card-nums-box">
                                    <h4>17,5%</h4>
                                    <h4>90 дней</h4>
                                </div>
                                <div class="main__user-content-card-nums-box">
                                    <p>Доходность, до</p>
                                    <p>Срок вклада, от</p>
                                </div>
                            </div>

                            <p class="main__user-content-card-invest">
                                Доход выплачивается по окончании срока договора, возможно досрочное расторжение
                            </p>
                            <div class="main__user-content-card-btns">
                                <button>Инвестировать</button>
                                <button>Подробнее</button>
                            </div>
                        </div>
                    </div>

                    <div class="main__user-content-card">
                        <img src="@/assets/img/man2.png" alt="" />

                        <div class="main__user-content-card-shadow"></div>
                        <div class="main__user-content-card-bottom">
                            <p class="main__user-content-card-invest">Инвестиции</p>
                            <h3>Вклад Активный</h3>

                            <div class="main__user-content-card-nums">
                                <div class="main__user-content-card-nums-box">
                                    <h4>16,5%</h4>
                                    <h4>90 дней</h4>
                                </div>
                                <div class="main__user-content-card-nums-box">
                                    <p>Доходность, до</p>
                                    <p>Срок вклада, от</p>
                                </div>
                            </div>

                            <p class="main__user-content-card-invest">
                                Доход выплачивается по окончании срока договора, возможно досрочное расторжение
                            </p>
                            <div class="main__user-content-card-btns">
                                <button>Инвестировать</button>
                                <button>Подробнее</button>
                            </div>
                        </div>
                    </div>

                    <div class="main__user-content-card">
                        <img class="man3" src="@/assets/img/man3.png" alt="" />

                        <div class="main__user-content-card-shadow"></div>
                        <div class="main__user-content-card-bottom">
                            <p class="main__user-content-card-invest">Инвестиции</p>
                            <h3>Вклад Комфорт</h3>

                            <div class="main__user-content-card-nums">
                                <div class="main__user-content-card-nums-box">
                                    <h4>17,5%</h4>
                                    <h4>90 дней</h4>
                                </div>
                                <div class="main__user-content-card-nums-box">
                                    <p>Доходность, до</p>
                                    <p>Срок вклада, от</p>
                                </div>
                            </div>

                            <p class="main__user-content-card-invest">
                                Доход выплачивается по окончании срока договора, возможно досрочное расторжение
                            </p>
                            <div class="main__user-content-card-btns">
                                <button>Инвестировать</button>
                                <button>Подробнее</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="main__ques">
            <div class="container">
                <div class="main__ques-content">
                    <div class="main__ques-content-left">
                        <p>
                            У вас остались вопросы? <br />
                            <span>Закажите консультацию специалиста</span>
                        </p>
                        <p>Мы подробно ответим на все ваши вопросы и подберем наиболее удобный вариант вклада</p>
                        <div class="main__ques-content-left-btns">
                            <button>Заказать консультацию</button>
                            <button>Онлайн чат</button>
                        </div>
                    </div>
                    <div class="main__ques-content-right">
                        <img src="@/assets/img/man4.png" alt="" />
                        <img src="@/assets/img/shape-bg.svg" alt="" />
                    </div>
                </div>
            </div>
        </section>

        <section class="main__model">
            <div class="container">
                <div class="main__model-content">
                    <h2 class="main__model-content-title">Модель работы</h2>
                    <div class="main__model-content-box">
                        <div class="main__model-content-box-lft">
                            <p class="main__model-content-box-lft-title">Ваш инвестиционный вклад</p>
                            <div class="main__model-content-box-lft-block">
                                <img src="@/assets/img/model1.png" alt="" />
                                <div class="main__model-content-box-lft-block-texts">
                                    <p>
                                        Инвестор <br />
                                        фонда
                                    </p>
                                    <p>
                                        Доход инвестора <br />
                                        по вкладу
                                    </p>
                                </div>
                            </div>
                        </div>
                        <div class="main__model-content-box-mddl">
                            <img class="" src="@/assets/img/right.svg" alt="">
                            <img class="" src="@/assets/img/left.svg" alt="">
                            <img src="@/assets/img/center.png" alt="" />
                            <img class="" src="@/assets/img/right.svg" alt="">
                            <img class="" src="@/assets/img/left.svg" alt="">
                        </div>
                        <div class="main__model-content-box-rgt">
                            <p class="main__model-content-box-lft-title">Финансирование</p>
                            <div class="main__model-content-box-lft-block">
                                <img src="@/assets/img/model.png" alt=""
                                    class="main__model-content-box-lft-block-pics2" />
                                <div class="main__model-content-box-lft-block-texts">
                                    <p>
                                        Инвестор <br />
                                        фонда
                                    </p>
                                    <p>
                                        Доход инвестора <br />
                                        по вкладу
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>
