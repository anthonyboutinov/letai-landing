# Letai: New Tariffs “A Whole Lot”—Landing Page

_October, 2020_

**<a href="https://www.behance.net/gallery/154223311/Letai-Landing-Page">Behance Page</a>**

<a href="https://www.behance.net/gallery/154223311/Letai-Landing-Page"><img src="/readme-images/letai-behance-website-preview.jpg" alt="Letai Project Banner"></a>

Screenshot:

<img src="/readme-images/letai-index-html.png" alt="Letai Preview">

A snapshot of that version of the website is available on Wayback Machine: https://web.archive.org/web/20201016044011/https://mnogo.letai.ru/

## Установка

Для разработки, постройте node_modules

```
npm install
```

## Использование

### Разработка / Serve

Запустить проект на локальном сервере:

```
grunt
```

Можно писать JS на ECMAScript 2015+ (используется Babel 7)

### Сборка проекта для продакшена / Build

В `Gruntfile.js` укажите адрес папки с темой в переменной `themePath`. Во время сборки, это значение будет подставлено во все упоминания `@{themePath}` в JS и SCSS коде (например, в src изображений).

```
grunt build
```

JS файлы конкатенируются и проходят через Babel; изображения, JS, HTML, SASS сжимаются; в CSS добавляются вендор-префиксы и rem-fallback; содержимое public переносится без изменения.

## Поддержка

Project created by Anthony Boutinov (@anthonyboutinov) https://boutinov.website
