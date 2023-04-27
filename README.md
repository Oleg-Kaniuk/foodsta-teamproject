ТАК, УСІМ ПРИВІТ. НАРЕШТІ ДОЛІЗ ДО КОМПА.

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

3. ДЛЯ HEADER\_\_ (ім'я тегу - назва крласу)

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

І ПЕРЕБИВАЙТЕ АБО Ж ДОДАВАЙТЕ ЦІ ВЛАСТИВОСТІ ТОЧКОВО (ЛИШЕ ТАМ ДЕ ПОТРІБНО)
