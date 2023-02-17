<h2 id="start"> Проект с курса: "Комплексное обучение JavaScript" <br> (Школа Loftschool)

___
### 📄 Описание:
Веб-приложение, которое отображает Яндекс карту. На карте вы можете выбирать объекты и оставлять отзывы о них. Проект реализован в сборщике Webpack, предоставленный школой Loftschool.

### 📃 Использование и функционал:
При клике на карту в выбранном месте создаётся окно `balloon` с вводом данных, в данном случае мы реализуем краткий отзыв. После ввода данных и их  отправки, данные сохраняются в `LocalStorage` и на указанном месте создаётся метка `placemark`, при клике на которую мы можем вновь добавить ещё сколько угодно нам отзывов и просматривать уже имеющиеся. При уменьшении масштаба `zoom` нашей карты, метки трансформируются в кластеры `clusterer`, при увеличении же всё наоборот, кластер визуально распадается на отдельные от остальных метки и/или же на другие кластеры.

### ⚙ Стек технологий:
- Webpack
- Handlebars
- API Яндекс-карт
  + JavaScript
  + HTML
  + CSS
___
###### [Вернуться вверх](#start) 👆
