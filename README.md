# Проект «CGallery»

За время стажировки тебе предстоит реализовать сервис наподобие Инстаграма.

В [index.html](./index.html) ты найдешь основу для верстки. Ты можешь менять её под себя, либо вообще сверстать проект с нуля

## Как работать с версткой

Давай разберем основные моменты, чтобы тебе было проще работать с заготовкой, если ты все же решишь ее использовать.

### Скрытие / показ элементов

Для скрытия HTML-элементов с помощью `display: none` используется класс `.hidden`.

Если же тебе нужно спрятать элемент, сохранив его место в документе (чтобы контент не «прыгал»), используй класс `.v-hidden`.

### Модальные окна

В верстке сейчас присутствует три модальных окна:

- Добавление нового поста `.add-post-modal`
- Просмотр поста `.preview-post-modal`
- Редактирование пользовательских данных `.edit-bio-modal` (повышенный уровень сложности)

По умолчанию модальные окна скрыты. Для показа интересующего тебя модального окна, добавь ему класс `.active`. (`.modal.active` в [CSS-файле](./style.css))

### Запрет прокрутки

При открытии любого модального окна на заднем плане должен появиться темный оверлэй, запрещающий прокрутку.

Для этого добавь класс `.with-overlay` на body (`body.with-overlay` в [CSS-файле](./style.css)) и класс `.active` элементу `.body-overlay` (`.body-overlay.active` в [CSS-файле](./style.css))

### Закрытие модальных окон

Все модальные окна должны закрываться по клику на внешнюю область (можешь добавить обработчик на оверлэй)

На этом с общими рекомендациями по верстке все — идем дальше 🙂

## Рекомендации по JS

Перед началом написания кода внимательно ознакомься с [критериями](https://docs.google.com/spreadsheets/d/1oa5-hl-jiYb1PBvKOd-wsdVvrvJagNTeQZBKpdcsunw/edit#gid=0).

Куда проще изначально ориентироваться на них, чем потом править весь код проекта в последний момент.

Советую разбить свой код на [модули](https://learn.javascript.ru/modules-intro) по смыслу.

Так, например, один файл у тебя будет отвечать за добавление постов, а другой — за лайки и комментарии. Меньше кода в одном файле — проще ориентироваться в написанном.

## Как работать с бэкендом

Важные моменты взаимодействия с бэкендом описаны [в этой памятке](./task/work-with-backend.md).

**Обязательно** прочитай ее перед началом работы.

На стажировке ты встретишься с новым для тебя инструментом _Swagger_. Он очень популярен в айти-компаниях и облегчает общение фротенд- и бэкенд-разработчиков.

## Техническое задание

Ниже представлено техническое задание, разделенное по неделям для твоего удобства

- [Первая неделя](./task/first-week.md)

- [Вторая неделя](./task/second-week.md)

- [Третья неделя](./task/first-week.md)

Четвертая неделя — бонусная. Во время нее ты сможешь доделать что не успела или заняться реализацией дополнительной функциональности вне ТЗ.

> P.S. ТЗ охватывает далеко не все возможности бэкенда, так что можешь поисследовать [доступное API](https://c-gallery.polinashneider.space/swagger/) бэкенда сама, или написать куратору.
