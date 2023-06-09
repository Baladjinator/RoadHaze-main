<h1 align="center">
  RoadHaze - Road Surface Detection and Hazard Analysis System
</h1>

<p align="center">
  <img src="https://github.com/Baladjinator/RoadHaze/blob/main/images/logo.png?raw=true"/>
</p>

## Съдържание:
* [Проблем](#problem)
* [Решение](#solution)
* [Избрана подтема](#topic)
* [Описание](#description)
* [Използвани технологии](#techs)
* [Нашият екип](#team)
* [Изображения](#demo)

<a name="problem"/>

## Проблем:
<p align="justify"> На 20 000 км републиканска пътна мрежа на територията на Република България съществуват стотици опасни участъци. Според пътна полиция и пътна агенция те са около 70, но реално са много повече. Сред най-критичните пътни отсечки е Кресненското дефиле. Самото дефиле е с много завои, ограничена скорост, липса на места за изпреварване, скални участъци, буйна река и натоварен трафик с тирове и чуждестранни автомобили. Това несъмнено са предпоставки за редица пътни инциденти.</p>


<a name="solution"/>

## Решение:
<p align="justify">RoadHaze представлява система, базирана на машинно самообучение, която наблюдава опасни пътни участъци в реално време и предоставя интеграция с мобилна апликация. По този начин потребителите на приложението могат да бъдат уведомявани за потенциални рискове, свързани с атмосферните условия, по време на тяхното пътуване.</p>


<a name="topic"/>

## Избрана подтема:
Избраната от нас подтема е Physical Security.


<a name="description"/>

## Описание:
<p align="justify">Системата RoadHaze се състои от два дяла - хардуерна и софтуерна част. Хардуерната част представлява микрокомпютър Raspberry Pi с инсталирини камера и GPS модул. Платката е захранвана от мини фотоволтаична система, състояща се от 12V 25W фотоволтаичен панел, соларен контролер и 12V 8Ah LiFePO4 батерия. През определен интервал от време снимките от камерата се изпращат на FastAPI сървър. Там те биват обработени от изкуствен интелект, който връща информация за състоянието на опасния пътен участък, на който е поставена камерата. Към системата е разработено иновативно мобилно приложение, което визуализира данните от GPS модула, камерата и изкуствения интелект по достъпен за обикновения потребител начин. Така RoadHaze помага на водачите да вземат информирани решения относно своя маршрут и поведение при шофиране.</p>


<a name="techs"/>

## Използвани технологии:
- Raspberry Pi (Embedded)
- FastAPI (Backend)
- PyTorch (AI)
- Flutter (Frontend)


<a name="team"/>

## Нашият екип:
- Алеко Георгиев - Backend Dev
- Кристиян Богданов - Frontend Dev
- Крум Стефанов - AI Dev
- Мартин Дацев - Mентор
- Никола Керезов - AI Dev
- Симеон Ангелов - Frontend Dev


<a name="demo"/>

## Изображения:
<p align="center">
  <img src="https://github.com/Baladjinator/RoadHaze/blob/main/images/embedded.jpg" height="400"/>
</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/853633838248099853/1083953578047180881/image0.jpg" height="400"/>
</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/853633838248099853/1083952841804222474/SmartSelect_20230311_052054.jpg" height="400"/>
</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/853633838248099853/1083952841590317126/SmartSelect_20230311_051840.jpg" height="400"/>
</p>

