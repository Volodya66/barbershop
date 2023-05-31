# barbershop

<!-- рут -->

<!-- светлый фон -->

#E5E5E5 - bg-light-theme

<!-- заголовки для секций, где светлый фон -->

#303030 - это title-light-theme

<!-- текст, где светлый фон -->

#555555 - это text-light-theme
#F7F7F7 - alternative-bg-color
#FF6C00 - hover-color
#9DA4BD - text-dark-theme
#FFFFFF - title-dark-theme

<!-- контейнер для десктопу -->

.container {
width:1200px;
padding-left:15px;
padding-right:15px;
}

<!--  назви для тексту-->

.link-header {
font-weight: 600;
font-size: 12px;
line-height: 1.33; //16px
letter-spacing: 0.1em;
}

.button-text {
font-family: 'Open Sans';
font-style: normal;
font-weight: 600;
font-size: 12px;
line-height: 1.33; //16px
letter-spacing: 0.09em;
}

.section-info {
font-weight: 600;
font-size: 11px;
line-height: 1.36; // 15px
letter-spacing: 0.1em;
}

.middle-text {
font-weight: 400;
font-size: 18px;
line-height: 1.67; // 30px
letter-spacing: 0.02em;
}

.small-text {
font-weight: 400;
font-size: 14px;
line-height: 1.86; // 26px
let
ter-spacing: 0.02em;
}
.section-title {
font-family: 'Raleway';
font-weight: 700;
font-size: 42px;
line-height: 1.17; // 49px
letter-spacing: 0.05em;
}

.title-numbers {
font-weight: 700;
font-size: 42px;
line-height: 1.36; // 57px
letter-spacing: 0.05em;
}

.name-workers {
font-weight: 400;
font-size: 18px;
line-height: 1.39; //25px
letter-spacing: 0.02em;
}

.job-workers {
font-weight: 400;
font-size: 14px;
line-height: 1.36; // 60px
letter-spacing: 0.02em;
}

.link-text {
font-weight: 600;
font-size: 11px;
line-height: 1.36; // 15px
letter-spacing: 0.2em;
}

<!--  -->

h1,
h2,
h3,
h4,
h5,
h6,
p {
margin: 0;
}

img {
display: block;
max-width: 100%;
height: auto;
}

button {
cursor: pointer;
border: none;
}

ul,
ol {
list-style: none;

margin: 0;

padding-left: 0;
}

a {
text-decoration: none;
}

.container {
по макету
}

.section {
по макету
}

.visually-hidden {
position: absolute;
white-space: nowrap;
width: 1px;
height: 1px;
overflow: hidden;
border: 0;
padding: 0;
clip: rect(0 0 0 0);
clip-path: inset(50%);
margin: -1px;

}

.contacts {
background-color: #191C26;
}
/_Задний фон Контактов_/
/_Mobile contacts image_/
@media screen and (max-device-pixel-ratio: 1) and (max-width: 767px),
screen and (max-resolution: 96dpi) and (max-width: 767px),
screen and (max-resolution: 1dppx) and (max-width: 767px) {
.contacts {
background-image: linear-gradient(rgba(25, 28, 38, 0.9), rgba(25, 28, 38, 0.9)),
url(../images/mobile-bg-contacts.jpg);
}
}
/_ Screen 2px - before 768px _/
@media screen and (min-device-pixel-ratio: 2) and (max-width: 767px),
screen and (min-resolution: 192dpi) and (max-width: 767px),
screen and (min-resolution: 2dppx) and (max-width: 767px) {
.contacts {
background-image: linear-gradient(rgba(25, 28, 38, 0.9),
rgba(25, 28, 38, 0.9)),
url('../images/mobile-bg-contacts-2x.jpg');
}
}
/_ Tablet contacts image _/
@media screen and (max-divice-pixel-ratio: 1) and (min-width: 768px) and (max-width: 1199px),
screen and (max-resolution: 96dpi) and (min-width: 768px) and (max-width: 1199px),
screen and (max-resolution: 1dppx) and (min-width: 768px) and (max-width: 1199px) {
.contacts {
background-image: linear-gradient(rgba(25, 28, 38, 0.9),
rgba(25, 28, 38, 0.9)),
url('../images/tablet-bg-contacts.jpg');
}
}
/_ Tablet contacts image 2px _/
@media screen and (min-device-pixel-ratio: 2) and (min-width: 768px) and (max-width: 1199px),
screen and (min-resolution: 192dpi) and (min-width: 768px) and (max-width: 1199px),
screen and (min-resolution: 2dppx) and (min-width: 768px) and (max-width: 1199px){
.contacts {
background-image: linear-gradient(rgba(25, 28, 38, 0.9),
rgba(25, 28, 38, 0.9)),
url('../images/tablet-bg-contacts-2x.jpg');
}
}
/_ Desktop contacts image _/
@media screen and (max-device-pixel-ratio: 1) and (min-width: 1158px),
screen and (max-resolution: 96dpi) and (min-width: 1158px),
screen and (max-resolution: 1dppx) and (min-width: 1158px) {
.contacts {
background-image: linear-gradient(rgba(25, 28, 38, 0.9),
rgba(25, 28, 38, 0.9)),
url('../images/desktop-bg-contacts.jpg');
}
}
/_ Desktop contacts image 2px _/
@media screen and (min-device-pixel-ratio: 2) and (min-width: 1158px),
screen and (min-resolution: 192dpi) and (min-width: 1158px),
screen and (min-resolution: 2dppx) and (min-width: 1158px) {
.contacts {
background-image: linear-gradient(rgba(25, 28, 38, 0.9),
rgba(25, 28, 38, 0.9)),
url('../images/desktop-bg-contacts-2x.jpg');
}
}
