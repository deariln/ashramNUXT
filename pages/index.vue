<template>
    <section id="main-page">
        <div class="textpic">
            <!-- <img src="photo/main.jpg" alt="main-logo" id="main-logo"> -->
            <div class="text">
                <h1 class="h1">ASHRAM</h1>
                <p>Почасовая аренда рабочего места для мастеров индустрии красоты</p>
                <div>
                    <button class="buttonpic1">Забронировать место</button>
                    <a href="#rules" class="buttonpic2">Правила аренды</a>
                </div>
            </div>
        </div>
    </section>

    <div id="service" class="service">
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

    <section id="places" class="places-page">
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
    <section id="rules" class="rules-page">
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

    <section class="answers-page" id="qestion">
        <div class="h5">
            <h5>Ответы на частые вопросы</h5>
        </div>
        <div class="qestion">
            <div class="window">
                <div class="icon">
                    <p>Что входит в стоимость?</p>
                    <button @click="toggleQestion('qestion')" class="qwe-butt">
                        <img class="img-qestions" src="/photo/arrow.png" alt="">
                    </button>
                </div>
                <div v-if="isOpen === 'qestion'" class="answer">
                    <ul class="ul-answer">
                        <li>- рабочего место</li>
                        <li>- расходные материалы</li>
                        <li> - оборудование для фото и видео</li>
                        <li>- чай, кофе, вода, сладости</li>
                    </ul>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <p>Как происходит оплата?</p>
                    <button @click="toggleQestion('qestion2')" class="qwe-butt">
                        <img class="img-qestions" src="/photo/arrow.png" alt="">
                    </button>
                </div>
                <div v-if="isOpen === 'qestion2'" class="answer">
                    <ul class="ul-answer">
                        <li> Оплата происходит сразу же после работы переводом или наличными</li>
                        <li>Аренда гримерного стола: 125 ₽ за 30 минут</li>
                        <li>Аренда кабинета "Стандарт": 150 ₽ за 30 минут</li>
                        <li>Аренда кабинета "Комфорт": 175 ₽ за 30 минут</li>
                    </ul>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <p>Есть ли администратор?</p>
                    <button @click="toggleQestion('qestion3')" class="qwe-butt">
                        <img class="img-qestions" src="/photo/arrow.png" alt="">
                    </button>
                </div>
                <div v-if="isOpen === 'qestion3'" class="answer">
                    Обращаем ваше внимание, что в пространстве вы находитесь одни. Администратор работает удаленно, и вы
                    можете написать ему по любому вопросу
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <p>Как забронировать место?</p>
                    <button @click="toggleQestion('qestion4')" class="qwe-butt">
                        <img class="img-qestions" src="/photo/arrow.png" alt="">
                    </button>
                </div>
                <div v-if="isOpen === 'qestion4'" class="answer">
                    <ul class="ul-answer">
                        <li> Аренда рабочих мест осуществляется по предварительному бронированию без предоплаты до 5ч
                            аренды. От 5
                            часов - предоплата в размере 100%.
                            Вы можете совершить бронирование любым из удобных для вас способов:</li>
                        <li>1. С помощью сообщения в wa +7 993 768 63 15</li>
                        <li>2. На сайте через форму онлайн-записи</li>
                    </ul>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <p>Как перенести или отменить бронь?</p>
                    <button @click="toggleQestion('qestion5')" class="qwe-butt">
                        <img class="img-qestions" src="/photo/arrow.png" alt="">
                    </button>
                </div>
                <div v-if="isOpen === 'qestion5'" class="answer">
                    <ul class="ul-answer">
                        <li>Вы можете перенести/отменить бронь любым из удобных для Вас способов:</li>
                        <li>1. С помощью сообщения в wa +7 993 768 63 15</li>
                        <li>2. На сайте через форму онлайн-записи</li>
                        <li>В случае отмены брони:</li>
                        <li>— Отмена или перенос менее чем за 24ч – оплата 100%</li>
                    </ul>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <p>Какие расходные материалы входят в стоимость?</p>
                    <button @click="toggleQestion('qestion6')" class="qwe-butt">
                        <img class="img-qestions" src="/photo/arrow.png" alt="">
                    </button>
                </div>
                <div v-if="isOpen === 'qestion6'" class="answer">
                    <ul class="ul-answer">
                        <li>Мы предоставляем расходные материалы бесплатно:</li>
                        <li>- ватные диски,</li>
                        <li>- ватные палочки,</li>
                        <li>- одноразовые простыни,</li>
                        <li>- бумажные полотенца,</li>
                        <li>- влажные салфетки,</li>
                        <li>- антисептик.</li>
                        <li>Также у нас можно приобрести:</li>
                        <li>- перчатки 30 руб/шт</li>
                        <li>- крафт пакет 10 руб/шт</li>
                        <li>- патчи 10 руб/шт</li>
                    </ul>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <p>Можно ли занять место раньше?</p>
                    <button @click="toggleQestion('qestion7')" class="qwe-butt">
                        <img class="img-qestions" src="/photo/arrow.png" alt="">
                    </button>
                </div>
                <div v-if="isOpen === 'qestion7'" class="answer">
                    Только по согласованию с администратором, даже если место свободно. Вы можете связаться с
                    администратором в чате WA +7 993 768 63 15
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <p>Есть ли абонементы?</p>
                    <button @click="toggleQestion('qestion8')" class="qwe-butt">
                        <img class="img-qestions" src="/photo/arrow.png" alt="">
                    </button>
                </div>
                <div v-if="isOpen === 'qestion8'" class="answer">
                    <ul class="ul-answer">
                        <li>Абонемент в гримерный зал:</li>
                        <li>20 часов - 4800 руб</li>
                        <li>40 часов - 9200 руб</li>
                        <li>Абонемент в кабинет "Стандарт":</li>
                        <li>20 часов - 5800 руб</li>
                        <li>40 часов - 11200 руб</li>
                        <li>Абонемент в кабинет "Комфорт":</li>
                        <li>20 часов - 6800 руб</li>
                        <li>40 часов - 13200 руб</li>
                    </ul>
                </div>
            </div>
            <div class="window">
                <div class="icon">
                    <p>Можно ли продлить бронь, если не успеваешь закончить?</p>
                    <button @click="toggleQestion('qestion9')" class="qwe-butt">
                        <img class="img-qestions" src="/photo/arrow.png" alt="">
                    </button>
                </div>
                <div v-if="isOpen === 'qestion9'" class="answer">
                    <ul class="ul-answer">
                        <li>Продлить бронь возможно только по предварительному согласованию с администратором, в ином
                            случае,
                            рабочее место необходимо освободить для работы следующего мастера.</li>
                        <li>— Задержка рабочего места более 10 минут, оплачивается по тарифу аренды 30/60 мин</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    <section class="sec-contacts" id="contacts">
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
const isOpen = ref(null)

const toggleQestion = (qestion:any) => {
    if (isOpen.value === qestion) {
        isOpen.value = null
    } else {
        isOpen.value = qestion
    }
}
</script>

<style></style>