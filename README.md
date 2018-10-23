# Яндекс • Школа разработки интерфесов


## Материалы лекции "Типизация"

### Обзор возможностей языка TypeScript https://github.com/shyr1punk/typescript-overview
### Пример миграции проекта на TypeScript https://github.com/shyr1punk/typescript-migrate

## Домашнее задание

### Переписать на TypeScript код следующих домашних заданий:
* ДЗ «Адаптивная вёрстка»
* ДЗ «Работа с сенсорным пользовательским вводом»
* ДЗ «Мультимедиа»
* ДЗ «Node js»

### Приложение должно остаться работоспособным!
**Важно:** Добавьте информацию для проверяющих о том как запустить компиляцию и сам проект, добавьте короткие команды в `npm scripts`.

По завершении проверки домашнего задания на ваше усмотрение останется выбор: вливать данный PR и дальше работать с TypeScript или не вливать и продолжать работать с JavaScript. В отчёте нужно мотивировать ваш выбор.

### Преимуществом будет:
* отсутствие явных и неявных типов `any`
* компиляция в строгом режиме (`"strict": true` в `tsconfig.json`)
* отсутствие `// @ts-ignore`, использования оператора `!` для подавления ошибок строгих проверок на `null`
* минимальное использование `type assertions`, как например `someVar as SomeType`

Для Node.JS допустимо как компилировать код в `*.js`, так и запускать из под [ts-node](https://github.com/TypeStrong/ts-node).
Для клиентских приложений можете выбрать любой способ компиляции:
* Если не используете инструменты сборки, то компилируйте в единственный файл, который подключите на страницу (как в примере c миграцией проекта)
* Если используете `webpack`, подключите `ts-loader` или `awesome-typescript-loader`
* Если используете `gulp`, используйте пакет `gulp-typescript`

### В отчёте отразить:
* Трудоёмкость перевода проекта на TypeScript. Самые сложные моменты в работе.
* Какие в процессе перевода были найдены ошибки.
* Решили ли вы вливать данный PR, или предпочитаете работать с JavaScript? Почему?
