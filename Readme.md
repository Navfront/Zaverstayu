# Проект марафона «Заверстаю 5.0»

### Ссылка на gh-pages: https://navfront.github.io/Zaverstayu/
---

## О проекте:

Марафон по верстке от HTML Academy

## ТЗ проекта:

- [x] Фиксированный размер
- [x] Использованы Flexbox и Grid
- [x] Стилизация всех интерактивных элементов в блоке "Наши работы"
- [x] Якорные ссылки в навигации
- [x] Кроссбраузерность
- [x] Переполнение не ломает верстку
- [x] Соблюдены базовые и дополнительные критерии качества

## Основные критерии качества:

- Проект должен быть сделан на HTML без использования сторонних библиотек и фреймворков.
- Текстовые параметры должны соответствовать параметрам из макета.
- Код должен быть написан с соблюдением требований кодгайда Академии.
- Названия папок, файлов, атрибутов, классов должны состоять из английских слов без сокращений.
- Файлы и папки должны быть записаны строчными буквами без пробелов между словами.
- В проекте не должно быть закомментированных фрагментов кода без осмысленного текстового пояснения.
- В проекте не должно быть неиспользуемых файлов.
- На странице, при их наличии, должны быть обозначены структурные ориентиры: 
  - `<header>` для вводной части, повторяющейся на других страницах;
  -	`<main>` для основного содержимого, не повторяющегося на других страницах;
  -	`<nav>` для важных навигационных элементов по сайту;
  - `<footer>` для закрывающей, дополнительной информации о странице.
- На странице должен быть `<h1>`, который описывает содержимое страницы.
- Уровни заголовков должны идти последовательно от большего к меньшему без пропусков.
- Ссылки `<a href>` должны использоваться для перехода между страницами, а кнопки `<button>` должны использоваться только для действий на странице.
  - У ссылок должен быть атрибут `href`. Ссылки, которые ведут на самих себя, могут быть без атрибута.
  - Для ссылок, адрес которых неизвестен, можно использовать атрибут `href` с решёткой `href="#"`.
  - Адреса почты и телефоны должны быть размечены ссылками с соответствующими схемами внутри href.
  - У кнопок должен быть явно указан тип действия в атрибуте type.
- Работоспособные формы:
  - Формы должны быть работоспособными и отправлять данные всех полей.
  - Поля формы должны находиться внутри тега `<form>`.
  - У формы должен быть указан атрибут `action`.
  - У обязательных полей должен быть атрибут required.
- Подписи полей форм должны быть привязаны к своим полям.
- В разметке не должно быть лишних обёрток и элементов, которые используются для оформления и могут быть заменены на псевдоэлементы.
- Разметка должна проходить валидацию в валидаторе `W3C` без ошибок (error).
В проверке могут быть предупреждения (warning).
- Подключение стилей:
  - Все стилевые файлы должны быть подключены с помощью тега `<link rel="stylesheet">`.
  - Собственные стили проекта должны быть подключены одним файлом в `<head>`.
  - Сторонние стили должны быть подключены в `<head>` отдельными файлами.
  - Сторонние стили должны быть подключены до собственных стилей проекта.
  - В разметке не должно быть инлайновых стилей в атрибуте `style=""` или в теге `<style>`.
  - В разметке допускаются стили для демонстрации поведения JS.
- Глобальные селекторы запрещены, кроме некоторых исключений.
- Глобальный селектор — это селектор по типу элемента или универсальный селектор.
- В селекторах не должно быть `#id`.
- Ключевое слово `!important` не должно использоваться для борьбы со специфичностью.
- Начертания шрифтов, подключенных с помощью `@font-face`, должны меняться с помощью `font-weight` и `font-style` и не должны меняться с помощью подключения отдельного семейства шрифтов.
- При указании шрифт должен дополняться общим семейством: `serif`, `sans-serif`, `monospace` и другие.
- Контентная графика должна вставляться в разметке.
- Декоративная графика должна вставляться в стилях.
- Декоративная SVG-графика может использоваться в разметке, если её внешний вид нужно менять стилями.
- Выбран подходящий формат изображений.
- Для всех изображений, размеченных при помощи `<img>` и `<svg>`, размеры должны быть заданы с помощью атрибутов `width` и `height`.
- Текст не должен переноситься с помощью двойного `<br>`.
- Контентная графика должна иметь описание.
- Интерактивные элементы должны быть подписаны. Подпись должна быть связана с элементом и отображаться в дереве доступности. Предпочтительно реализовывать подпись с помощью HTML: тегом с классом `visually-hidden` или атрибутом `alt` у изображений, и только потом — `aria`-атрибутами.
- Подпись в конце описания должна иметь точку. Точка нужна для интонационной паузы при чтении скринридером.
- Для блока, у которого есть текст с фоновым изображением, должен быть указан фоновый цвет, который соответствует преобладающему цвету изображения. Преобладающий цвет фоновой картинки должен быть контрастным.
