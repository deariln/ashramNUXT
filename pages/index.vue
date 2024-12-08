<template>
  <section id="main-page">
        <div id="textpic">
            <!-- <img src="photo/main.jpg" alt="main-logo" id="main-logo"> -->
            <div class="text">
                <h1 class="h1">ASHRAM</h1>
                <p>Почасовая аренда рабочего места для мастеров индустрии красоты</p>
                <div>
                    <button id="buttonpic1">Забронировать место</button>
                    <button id="buttonpic2">Правила аренды</button>
                </div>
            </div>
        </div>
    </section>

    <div id="service">
        <h2 class="h2">Каталог услуг</h2>
        <p class="p-service">Раннее бронирование — по будням с 08:00 бесплатно</p>
        <!-- <img class="img-service" src="/photo/ashram.gray.jpg" alt="img"> -->
    </div>
    <section class="service-page">
        <div class="box-item">
            <div class="icons">
                <div class="card">
                    <img class="img-icons" src="/photo/location.png" alt="location">
                    <p class="text-p">Удобное расположение в центре Сочи</p>
                </div>
            </div>
            <div class="icons">
                <div class="card">
                    <img class="img-icons" src="/photo/time.png" alt="time">
                    <p class="text-p">Почасовая аренда или абонементы со скидкой до 20%</p>
                </div>
            </div>
            <div class="icons">
                <div class="card">
                    <img class="img-icons" src="/photo/chair.png" alt="equipment">
                    <p class="text-p">Полностью оборудованные рабочие места, не нужно ничего докупать</p>
                </div>
            </div>
            <div class="icons">
                <div class="card">
                    <img class="img-icons" src="/photo/phone.png" alt="reserve">
                    <p class="text-p">Онлайн-бронирование и оплата, бесплатная отмена до определенного времени</p>
                </div>
            </div>
            <div class="icons">
                <div class="card">
                    <img class="img-icons" src="/photo/pot.png" alt="tea">
                    <p class="text-p">Бесплатные расходники, чай и кофе для вас и ваших клиентов</p>
                </div>
            </div>
        </div>
    </section>

    <section class="places-page">
        <div class="places">
            <h3 class="h3">Рабочие места</h3>
            <p class="p-places-page">Выбирайте подходящее место и работайте с комфортом, не заботясь ни о чем, кроме
                своего любимого дела.
                Мы уже продумали все необходимое для вашей продуктивной работы!</p>
        </div>
        <div class="cab1">
            <div class="head-cab1">
                <h1 class="h1-cab1">Гримерный зал</h1>
                <p class="p-cab1">250 руб/час</p>
            </div>
            <!-- <div class="cont-ul-cab1">
                <ul class="ul-cab1">
                    <li>2 гримерных места</li>
                    <li> Расходные материалы входят в стоимость</li>
                    <li>В гримерке стоит кулер</li>
                    <li>Чай, кофе, вода, сладости</li>
                    <li>Аренда хранения материалов</li>
                    <li> Оборудование для фото и видео</li>
                </ul>
            </div> -->
            <div class="container-photo">
                <div class="cab1-photo1">
                    <img class="img-cab1" src="/photo/ashram-4.jpg" alt="">
                </div>
                <div class="cab1-photo1">
                    <img class="img-cab1" src="/photo/ashram-5.jpg" alt="">
                </div>
            </div>
            <div class="button-cab">
                <NuxtLink to="/cab_one" class="but-cab">
                    Подробнее
                </NuxtLink>
            </div>
        </div>
        <div class="cab1">
            <div class="head-cab1">
                <h1 class="h1-cab1">Кабинет "Комфорт"</h1>
                <p class="p-cab1">350 руб/час</p>
            </div>
            <!-- <div class="cont-ul-cab1">
                <ul class="ul-cab1">
                    <li>Кушетка у которой поднимается спинка</li>
                    <li>Гримерный стол</li>
                    <li>Расходные материалы</li>
                    <li>Аренда хранения материалов</li>
                    <li> Оборудование для фото и видео</li>
                </ul>
            </div> -->
            <div class="container-photo">
                <div class="cab1-photo1">
                    <img class="img-cab1" src="/photo/ashram-7.jpg" alt="">
                </div>
                <div class="cab1-photo1">
                    <img class="img-cab1" src="/photo/ashram-3.jpg" alt="">
                </div>
            </div>
            <div class="button-cab">
                <button class="but-cab">Подробнее</button>
              </div>
        </div>
        <div class="cab1">
            <div class="head-cab1">
                <h1 class="h1-cab1">Кабинет "Стандарт"</h1>
                <p class="p-cab1">300 руб/час</p>
            </div>
            <!-- <div class="cont-ul-cab1">
                <ul class="ul-cab1">
                    <li>Гримерный стол</li>
                    <li>Кушетка с вырезом для лица</li>
                    <li>Мягкий ортопедический массаж</li>
                    <li>Расходные материалы</li>
                    <li>Аренда хранения материалов</li>
                    <li>Оборудование для фото и видео</li>
                </ul>
            </div> -->
            <div class="container-photo">
                <div class="cab1-photo1">
                    <img class="img-cab1" src="/photo/ashram-2.jpg" alt="">
                </div>
                <div class="cab1-photo1">
                    <img class="img-cab1" src="/photo/ashram-5.jpg" alt="">
                </div>
            </div>
            <div class="button-cab">
              <button class="but-cab">Подробнее</button>
            </div>
        </div>
    </section>
    <section class="rules-page">
        <div class="rules">
            <div class="rules-cont">
                <h1 class="h1-rules">Правила и договор аренды</h1>
                <p class="p-rules">Мы стараемся создать комфортную атмосферу для наших мастеров и их клиентов.
                    Для этого в нашем пространстве предусмотрены простые правила пребывания. Они касаются бронирования,
                    поддержания чистоты, уважения к другим мастерам и ответственности за свои вещи и действия.

                    Пожалуйста, ознакомьтесь с полным текстом правил и договором оферты перед арендой. Бронируя место,
                    вы
                    автоматически принимаете все условия.

                    Давайте сделаем наш коворкинг местом, куда приятно приходить каждый день.
                </p>
                <div class="button-rules">
                    <NuxtLink to="/rules_one" class="rules-one">
                        Правила аренды
                   </NuxtLink>
                   <NuxtLink to="/rules_two" class="rules-two">
                    Договор офферты
                   </NuxtLink>
                </div>
            </div>
        </div>

    </section>
   
    <section class="answers-page">
        <div class="h5">
            <h5>Ответы на частые вопросы</h5>
        </div>
        <div class="qestion">
            <div class="window">
                <div class="icon">
                    <img class="img-qestions" src="/photo/arrow.png" alt="">
                    <p>Что входит в стоимость?</p>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <img class="img-qestions" src="/photo/arrow.png" alt="">
                    <p>Как происходит оплата?</p>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <img class="img-qestions" src="/photo/arrow.png" alt="">
                    <p>Есть ли администратор?</p>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <img class="img-qestions" src="/photo/arrow.png" alt="">
                    <p>Как забронировать место?</p>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <img class="img-qestions" src="/photo/arrow.png" alt="">
                    <p>Как перенести или отменить бронь?</p>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <img class="img-qestions" src="/photo/arrow.png" alt="">
                    <p>Какие расходные материалы входят в стоимость?</p>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <img class="img-qestions" src="/photo/arrow.png" alt="">
                    <p>Можно ли занять место раньше?</p>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <img class="img-qestions" src="/photo/arrow.png" alt="">
                    <p>Есть ли абонементы?</p>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <img class="img-qestions" src="/photo/arrow.png" alt="">
                    <p>Можно ли продлить бронь, если не успеваешь закончить?</p>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <img class="img-qestions" src="/photo/arrow.png" alt="">
                    <p>Есть ли парковка?</p>
                </div>
            </div>
        </div>
    </section>
    <section class="sec-contacts">
        <div class="map">
            <h1 class="h1-map">Контакты</h1>
            <!-- <div>
                <img class="ashram-map" src="/photo/logo.PNG" alt="">
            </div> -->
            <div class="map-div">
                <div class="h2-map">
                    <h2 class="h-map">Адрес</h2>
                    <p>Сочи,
                        Курортный проспект 50/2,
                        4 этаж</p>
                </div>
                <div class="h2-map">
                    <h3 class="h-map">Время работы</h3>
                    <p>Ежедневно с 9:00 до 22:00</p>
                </div>
                <div class="h2-map">
                    <h4 class="h-map">Для связи</h4>
                    <p>8 993 768 63 15 WA</p>
                </div>
            </div>
            <!-- <div class="frame">
                <iframe
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1445.218924660521!2d39.729501427567314!3d43.57659549638826!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x40f5cb904809aacb%3A0xc906e8fc9a1d7938!2z0JzQsNCz0L3QvtC70LjRjyDQvtGC0LXQu9GM!5e0!3m2!1sru!2sru!4v1731957633422!5m2!1sru!2sru"
                    width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"
                    referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div> -->
        </div>
    </section>

</template>

<script setup lang="ts">
</script>

<style>
</style>