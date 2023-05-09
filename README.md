І ТАК КОМАНДА FOODSTA УСІМ ПРИВІТ

ПОПЕРЕДНІЙ КОМЕНТАР БУДЕ НИЖЧЕ І ВІН ЗАКОМЕНТОВАНИЙ (МОЖЛИВО ЩЕ КОМУСЬ БУДЕ ПОТРІБНА ЯКАСЬ ІНФОРМАЦІЯ)

РОЗРОБЛЯЄМО СВОЇ СЕКЦІЇ ЗГІДНО КРИТЕРІЇВ ДЗ4 - ДЗ6

ТЕРМІН ВИКОНАННЯ (ЗА МОЖЛИВОСТІ) 25.05.2023

ЯКЩО КИДАЄТЕ МЕНІ ДЕКІЛЬКА КОММІТІВ ОДНОЧАСНО, ВКАЗУЙТЕ БУДЬ ЛАСКА ЯКИЙ ОСТАННІЙ (ПІДПИСУЙТЕ ЛОГІЧНО І ЗРОЗУМІЛО)

ОТЖЕ ЩО ЗРОБИВ ЧИ ДОДАВ НОВОГО:

1. У КОЖНУ СЕКЦІЮ ЗАКИНУВ УСІ НЕОБХІДНІ КАРТИНКИ (УСІ ОПТИМІЗОВАНІ)

КАРТИНКИ ЩО ПОТРІБНІ ДЛЯ ВИКОНАННЯ ЗА КРИТЕРІЯМИ 7ДЗ МАЮТЬ ВІДПОВІДНІ ПРИСТАВКИ -tablet та -mobile

УСІМ У КОГО Є ФОН - СПОЗИЦІОНУВАТИ СВОЇ БЕКГРАУНДИ ЗГІДНО З МАКЕТОМ

(ДЛЯ ФУТЕРА БЕКГРАУНД ЗАДАЄ ОКСАНА М.)

(АСІ ЗАБРАТИ ЖОВТИЙ ФОН І ЗАДАТИ КАРТИНКУ)

2. УСІ ІКОНКИ ЗАКИНУВ У ЗАГАЛЬНИЙ СПРАЙТ <foodsta-icons>

УСІ ІКОНКИ ЗГЕНЕРОВАНІ І ОПТИМІЗОВАНІ

В УСІХ ІКОНОК ПОПРИБИРАВ fill, навіть там де не було потрібно (це для того, щоб ви могли на свою іконку задати інший колір при ховері, якщо захочете, хоча в макеті цього немає....це так для краси)

В УСІХ ІКОНОК ЗА ЗАМОВЧУВАННЯМ (DEFAULT) ЧОРНИЙ КОЛІР...

УСІ ІКОНКИ ПРАЦЮЮТЬ (САМ ПЕРЕВІРЯВ)

НЕ ЗАБУВАЙТЕ ІКОНКАМ ЗАДАВАТИ РОЗМІРИ (ЗА ЗАМОВЧУВАННЯМ ЦЕ 300 НА 150)

icon-arrow-left - СТРІЛКА ВЛІВО (ЗНАК МЕНШЕ)

icon-arrow-right - СТРІЛКА ВПРАВО (ЗНАК БІЛЬШЕ)

icon-btn-close - ХРЕСТИК ЗАКРИВАЮЧОЇ КНОПКИ

icon-burger-menu - БУРГЕР МЕНЮ

icon-rocket - РАКЕТА

icon-touch - ДОТИК

icon-star - ЗІРКА

3. ПІД'ЄДНАВ СКРИПТ ДЛЯ МОДАЛЬНОГО ВІКНА А ТАКОЖ ПРОПИСАВ В index.html ЗАГАЛЬНУ РОЗМІТКУ ДЛЯ НЬОГО (ЗГІДНО ІЗ НАШИМИ ДЗ)

ПРОСТАВИВ УСІ АТРИБУТИ: (data-modal-open, data-modal-close ТА data-modal)

data-modal-open ЗАДАВ НА УСІ КНОПКИ <ORDER NOW>

BACKDROP РОБИТЕ ТАКИЙ ЖЕ У НАШИХ ДЗ (ТОБТО НА ВСЮ ШИРИНУ І ВИСОТУ)

ВЗАГАЛІ ЩО СТОСУЄТЬСЯ МОДАЛЬНОГО ВІКНА - ТО РОБИТЕ ЙОГО ТАК САМО ЯК МИ РОБИЛИ У СЕБЕ (ТОБТО ЦЕНТРУВАННЯ І ВСЕ ТАКЕ)

РОЗМІРИ МОДАЛЬНОГО ВІКНА ЗГІДНО МАКЕТУ

4. УСІ INPUTИ ПОВИННІ БУТИ ЗГІДНО МАКЕТУ

INPUTИ ДЛЯ МОДАЛЬНОГО ВІКНА (ЦЕ ДЛЯ ТИХ У КОГО КНОПКИ -ORDER NOW-) БЕРЕМО ВАРІАНТ, ЩО СТОЇТЬ НАЙПРАВІШЕ У МАКЕТІ (З ОБОВ'ЯЗКОВИМ <REQUIED> ЗАПОВНЕННЯМ УСІХ ПОЛІВ)

ДЛЯ УСІХ INPUTів (ТАКОЖ ДЛЯ ТИХ У КОГО КНОПКИ SUBSCRIBE) ОБОВ'ЯЗКОВО МАЮТЬ БУТИ ПРОПИСАНІ УСІ НЕОБХІДНІ LABLE i PLACEHOLDER
(УСІ LABLE ТА PLACEHOLDER МІЖ СОБОЮ ПОВ'ЯЗАНІ)

НА УСІХ INPUTах ПОВИНЕН ПРАЦЮВАТИ ФОКУС, (АЛЕ НЕ ХОВЕР) ПРИ КЛАЦАННІ МИШКОЮ ЧИ ПЕРЕХОДІ З КЛАВІАТУРИ

5. ПІД'ЄДНАВ СКРИПТ ТА ЛІНКИ ДЛЯ SLIDER (КАРУСЕЛЬ) - ЦЕ ДЛЯ ДІМИ

У СКРИПТІ <slider.js> ПРОПИШЕШ ТОЙ СКРИПТ ЯКИЙ ПІДХОДИТЬ ТОБІ ЗА НАШИМ МАКЕТОМ

6. У ЗМІННУ ВИНІС (ЧАС ПЕРЕХОДУ ТА ФУНКЦІЮ РОЗПОДІЛУ ЧАСУ) {--transition-dur-and-func: 250ms cubic-bezier(0.4, 0, 0.2, 1);}  
   (ВЗЯВ ТАКИЙ ЖЕ У НАШИХ ДЗ)

НЕ ЗАБУВАЙТЕ ЗАДАВАТИ УСІ ПОТРІБНІ ПЕРЕХОДИ ДЕ ВОНИ У ВАС Є ПРИ ЗМІНІ СТАНУ ЕЛЕМЕНТУ

НАЧЕ ВСЕ.....Є ПИТАННЯ ....??? ЯКЩО ТАК, ТО ЗАДАВАЙТЕ)))

<!-- ТАК, УСІМ ПРИВІТ. НАРЕШТІ ДОЛІЗ ДО КОМПА.

СКАЖУ ОДРАЗУ ЩО ЦЕЙ МАКЕТ ЦЕ ЖАХ. ТУТ ПРАКТИЧНО НЕМАЄ НІЧОГО ЗАГАЛЬНОГО,

МАЙЖЕ У КОЖНІЙ СЕКЦІЇ СВОЇ LINE-HEIGHTu i FONT-SIZE

ТОМУ СПІЛЬНОГО (ЗАГАЛЬНОГО БУДЕ НЕ БАГАТО)

Я ЗВИЧАЙНО Ж ЩОСЬ ВИНЕСУ ЯК ЗАГАЛЬНЕ

ОБОВ'ЯЗКОВО ДОЧИТАЙТЕ ЦЕ ДО КІНЦЯ

ОТЖЕ ПОЇХАЛИ:

1. свої секції (всередині секції, футеру (ОКСАНА М) чи хедеру)
   усі огортаєте у DIV із загальним класом CONTAINER

2. усім секціям у MAIN задаєте загальний (основний) клас SECTION,
   у хедері - HEADER-PAGE, у футері - FOOTER

3. ДЛЯ HEADER\_\_ (ім'я тегу - назва класу)

a - logotype
img - logo-image

nav - nav-menu
ul - menu
li - menu-item
a - menu-link

button - modal-btn (не забувайте про type)

4. ДЛЯ HERO\_\_

   h1 - main-title
   p - section-text
   button - modal-btn
   img - hero-image

5. ДЛЯ OFFERINGS

img - offer-image
h2 - section-title
p - section-text
ul - offer-list
li - offer-item
h3 - section-subtitle
button - modal-btn

6. ДЛЯ FAVORITES

h2 - section-title
p - section-text
ul - favorite-list
li - favorite-item
img - favorite-image

7. ДЛЯ CUSTOMERS

h2 - section-title
p - section-text
ul - customers-list
li - customers-item
img - customers-image
h3 - section-subtitle

8. ДЛЯ SUBSCRIBE

h2 - section-title
p - section-text
button - modal-btn
img - subscribe-image

9. ДЛЯ FOOTER 1

a - logotype
img - logo-image

1 список

ul - menu
li - menu-item
a - menu-link

2 список

ul - terms-list
li - terms-item
a - terms-link

10. ДЛЯ FOOTER 2

h2 - section-title
button - modal-btn
p - section-text

ОТЖЕ ДО ТИХ СТИЛІВ ЩО У НАС ВЖЕ БУЛИ ДОДАЮ НАСТУПНІ:

button {
font-family: inherit;
cursor: pointer;
}

address {
font-style: normal;
}

img {
max-width: 100%
}

.modal-btn {
font-weight: 500;
font-size: 13px;
line-height: 1.54;
border-radius: 30px;
color: var(--primary-text-color);

.section-title {
font-weight: 700;
font-size: 42px;

color: var(--primary-text-color);
}

.section-text {
font-size: 16px;
line-height: 1.5;

color: var(--primary-text-color);
}

.section-subtitle {
font-weight: 700;
font-size: 18px;
line-height: 1.39;

color: var(--primary-text-color);
}

ЦЕ ВСЕ БУДЕ ЯК ЗАГАЛЬНЕ

ЯКЩО У ВАС ЩОСЬ АБО УСЕ НЕ СПІВПАДАЄ ІЗ ЗАГАЛЬНИМ

ТО БУДЬ ЛАСКА ЗАДАВАЙТЕ ДО ОСНОВНОГО КЛАСУ ЩЕ ДОДАТКОВИЙ

І ПЕРЕБИВАЙТЕ АБО Ж ДОДАВАЙТЕ ЦІ ВЛАСТИВОСТІ ТОЧКОВО (ЛИШЕ ТАМ ДЕ ПОТРІБНО) -->
