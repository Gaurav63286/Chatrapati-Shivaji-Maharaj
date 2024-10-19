::: {.nav}
[Home](#home){.active} [About](#about) [Timeline](#tribute-info) [More
Info](#tribute_link)
:::

::: {#main}
::: {#home .cover-image .overlay}
::: {#title}
#### Freedom is a boon, which everyone has the right to receive. {#freedom-is-a-boon-which-everyone-has-the-right-to-receive.}

# Chhatrapati Shivaji Maharaj
:::
:::

::: {#about .grid-container}
::: {.left}
## About

------------------------------------------------------------------------

Chhatrapati Shivaji Maharaj was the founder of the Maratha Empire in
western India. He is considered to be one of the greatest warriors of
his time and even today, stories of his exploits are narrated as a part
of the folklore. With his valor and great administrative skills, Shivaji
Maharaj carved out an enclave from the declining Adilshahi sultanate of
Bijapur. It eventually became the genesis of the Maratha Empire. After
establishing his rule, Shivaji Maharaj implemented a competent and
progressive administration with the help of a disciplined military and
well-established administrative set-up. Shivaji Maharaj is well-known
for his innovative military tactics that centered around
non-conventional methods leveraging strategic factors like geography,
speed, and surprise to defeat his more powerful enemies.
:::

::: {.right}
## Personal Info

------------------------------------------------------------------------

|                |                                                             |
|----------------|-------------------------------------------------------------|
| Name:          | Shivaji Bhosle                                              |
| Date-of Birth: | 19 February, 1630                                           |
| Birthplace:    | Shivenri Fort, Pune                                         |
| Parents:       | Shahaji Bhonsle (Father) and Jijabai (Mother)               |
| Spouse:        | Saibai, Soyarabai, Putalabai, Sakvarbai, Laxmibai, Kashibai |
| Death:         | 3 April, 1680                                               |
:::

::: {#tribute-info .down}
## Timeline of Shivaji Maharaj\'s Life

------------------------------------------------------------------------

- **February 19, 1630** - Birth of Shivaji Maharaj on the hill-fort of
  Shivneri
- **1630-1645** - Upbringing under the guidance of mother Jijabai and
  teacher Dadaji Kondev.
- **May 16, 1640** - Saibai and Shivaji Maharaj were married while still
  in their childhood.
- **1645** - Oath of Swarajya at Raireshwar temple
- **By 1645** - Shivaji Maharaj acquired control of several strategic
  from under the Bijapur Sultanate around Pune
- **November 10, 1659** - Shivaji Maharaj killed Afzal Khan at the foot
  of Pratapgad fort
- **Mid 1660** - Siege of Panhala by Siddi Jauhar\'s army.
- **July 13, 1660** - Battle of Pavan Khind
- **April 1663** - Attack on Shaista Khan
- **January 5, 1664** - Sack of Surat
- **June 11, 1665** - Treaty of Purandar
- **August 17, 1666** - Arrest in Agra and escape
- **Between 1666 - 1668:** - Peace with Mughals
- **February 4, 1670** - Battle of Sinhagad
- **October 2, 1670** - Shivaji Maharaj sacked Surat for second time.
- **June 6, 1674** - Shivaji Maharaj was crowned king of the Marathas in
  a lavish ceremony at Raigad.
- **End of 1676** - Conquest in Southern India
- **April 3, 1680** - Shivaji Maharaj died at the age of 52, on the eve
  of Hanuman Jayanti
:::
:::

::: {#img-div}
::: {#image}
![](https://raw.githubusercontent.com/snaily16/Freecodecamp-projects/master/tribute-page/rajyaabhishek1.jpg)
:::

::: {#img-caption}
Shivaji Maharaj\'s Coronation Ceremony at Raigad (6th June 1674)
:::
:::

::: {#tribute-link .more-info}
If you have time, you should read more about this incredible human being
on this:
[Wikipedia](https://en.wikipedia.org/wiki/Shivaji){#tribute_link}
:::
:::
------------------------------------------------------------------------

::: {.footer}
\-\-\-\-\-\-\-\-\--🚩Jai Shivaji Jai Bhavani🚩\-\-\-\-\-\-\-\-\--
:::

CSS
.nav {
    background-color: #ddd;
    overflow: hidden;
}

.nav a {
    float: left;
    color: black;
    text-align: center;
    padding: 10px 20px;
    text-decoration: none;
    font-size: 17px;
}

.nav a:hover {
    background-color: #444;
}

.nav a.active {
    background-color: #d40;
    color: white;
}

#main {
    text-align: center;
    background-color: #ccc;
}

.cover-image {
    background-image: url('974yqshn.png');
    min-height: 100%;
    height: 400px;
    padding-top: 450px;
    background-attachment: fixed;
    background-position: top;
    background-repeat: no-repeat;
    background-size: cover;
}

#title {
    position: absolute;
    padding-left: 2px;
    scroll-padding-top: 20000px;
}

#title h1 {
    font-family: Tangerine, Arial;
    text-shadow: 5px 5px 2px #823535;
    font-size: 140px;
    color: #f0580c;
    padding-top: -1px;
}

#title h4 {
    font-family: Cookie, Dancing Script, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-size: 60px;
    text-shadow: 2px 2px 2px #640;
    color: #e2dbdb;
    padding-top: -10px;
}

.grid-container {
    display: grid;
    grid-template-areas: 'left left left right right right' 'down down down down down down';
}

.left,
.right,
.down {
    height: 320px;
    margin: 5px;
}

.left {
    grid-area: left;
    padding: 30px 40px 10px 40px;
    background-color: rgb(228, 219, 208);
    border-radius: 10px;
    box-shadow: 0 4px 8px 0 rgba(198, 25, 25, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.right {
    grid-area: right;
    padding: 30px 40px 10px 40px;
    background-color: rgb(157, 168, 173);
    border-radius: 10px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.down {
    height: 720px;
    grid-area: down;
    padding: 30px 40px 10px 40px;
    background-color: #e1e7e2;
    border-radius: 10px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

hr.hr-style {
    margin-top: 0;
    border: 0;
    height: 2px;
    background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgb(90, 90, 90), rgba(0, 0, 0, 0));
}

.left h2,
.right h2,
.down h2 {
    font-family: Felipa, Serif;
    font-size: 35px;
    margin: 0px;
}

.left p {
    text-align: justify;
    font-family: Neucha, Dancing Script;
    font-size: 20px;
}

.right table {
    text-align: justify;
    font-family: Neucha, Dancing Script;
    font-size: 18px;
    padding: 10px;
}

.right td {
    padding: 8px;
}

@media (max-width: 600px) {
    .grid-container {
        grid-template-areas: 'left left left left left left' 'right right right right right right';
    }
}

.down ul {
    text-align: justify;
    font-family: Neucha, Dancing Script;
    font-size: 20px;
    padding: 20px;
    line-height: 1.7;
}

.down ul strong {
    background-color: rgba(240, 234, 234, 0.5);
    padding: 1px;
}

#img-div {
    margin: 10px 0px 20px 0px;
    width: 100%;
    height: auto;
    border-radius: 10px;
    background-color: rgb(235, 230, 230);
    padding-top: 20px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

#image {
    width: 100%;
    height: auto;
}

#img-caption {
    font-family: Neucha, Serif;
    font-size: 25px;
    padding: 5px;
}

.more-info p {
    border: dotted;
    border-radius: 10px;
    padding: 10px;
    font-size: 20px;
    font-family: Serif;
    margin: 20px;
    display: inline-block;
}

.more-info a {
    color: black;
    font-family: Neucha;
    font-weight: bold;
    background-color: #e9e8e7;
    display: inline-block;
    padding: 10px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    border-radius: 5px;
}

.more-info a:hover {
    background-color: #ada8a8;
}

.footer {
    font-family: Cookie, Arial;
    font-size: 30px;
    text-align: center;
}


