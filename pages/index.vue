<template>
    
    <section id="main-page">
        <div class="textpic">
            <div class="text">
                <p class="h1">ASHRAM</p>
                <p class="p-textpic">Почасовая аренда рабочего места для мастеров индустрии красоты</p>
                <div class="but-main_page">
                    <a href="https://dikidi.ru/1041348?p=0.pi" class="buttonpic1">Забронировать место</a>
                    <a href="#rules" class="buttonpic2">Правила аренды</a>
                </div>
            </div>
        </div>
    </section>
<!-- 
    <div id="service" class="service">
        <h2 class="h2">Каталог услуг</h2>
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
                    <p class="text-p">Почасовая аренда или  выгодные абонементы</p>
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
    </section> -->

    <section id="places" class="places-page">
        <div>
            <h1 class="h1-for_places">
                Рабочие места
            </h1>
        </div>
        <div class="container-places">
            <div class="places-card">
              <img class="places-card-image" src="/public/photo/place-card-1.jpeg" alt="#">
              <div class="plasec-list_text">
                  <h1 class="places-tittle">Гримерный зал</h1>
                  <p class="plasec-list_desc">250 руб/час</p>
              </div>
              <div class="button-cab">
                <NuxtLink to="/cab_one" class="but-cab">
                    Подробнее
                </NuxtLink>
            </div> 
            </div>
            <div class="places-card">
              <img class="places-card-image" src="/public/photo/place-card-2.jpeg" alt="#">
              <div class="plasec-list_text">
              <h1 class="places-tittle">Кабинет "Комфорт"</h1>
              <p class="plasec-list_desc">350 руб/час</p>
            </div>
            <div class="button-cab">
                <NuxtLink to="/cab_two" class="but-cab">
                    Подробнее
                </NuxtLink>
            </div> 
            </div>
            <div class="places-card">
              <img class="places-card-image" src="/public/photo/place-card-3.jpeg" alt="#">
              <div class="plasec-list_text">
              <h1 class="places-tittle">Кабинет "Стандарт"</h1>
              <p class="plasec-list_desc">300 руб/час</p>
            </div>
               <div class="button-cab">
                <NuxtLink to="/cab_three" class="but-cab">
                    Подробнее
                </NuxtLink>
            </div> 
            </div>
        </div>
    </section>
    <section id="rules" class="rules-page">
        <div class="rules-container">
            <div class="rules-images">
                <img class="img-for_rules" src="/public/photo/ashram-1.jpg" alt="">
            </div>
            <div class="rules-images">
              <div class="text-inside_rules">
                <p class="h1-rules_img">Правила и договор аренды</p>
                <p class="p-rules_img">Мы стараемся создать комфортную атмосферу для наших мастеров и их клиентов.
                    Для этого в нашем пространстве предусмотрены простые правила пребывания. Они касаются бронирования,
                    поддержания чистоты, уважения к другим мастерам и ответственности за свои вещи и действия.

                    Пожалуйста, ознакомьтесь с полным текстом правил и договором оферты перед арендой. Бронируя место,
                    вы
                    автоматически принимаете все условия.

                    Давайте сделаем наш коворкинг местом, куда приятно приходить каждый день.
                </p>
              </div>
              <div class="button-rules_img">
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

    <section class="sec-contacts" id="contacts">
        <div class="map">
            <h1 class="h1-map">Контакты</h1>
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
        </div>
    </section>

    <section class="answers-page" id="qestion">
        <div class="h5">
            <p>Ответы на частые вопросы</p>
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