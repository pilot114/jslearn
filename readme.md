# Что это?

"fullstack" JS фреймворк, написанный в учебных целях.

Ориентирован на то, чтобы облегчить самостоятельное изучение JavaScript и его приложения к разным областям разработки.
Родился из идеи что классическое обучение по общей программе неэффективно, а по индивидуальной - дорого.
Таким образом, мы приходим к формату "обучение по требованию" - информация даётся в том формате и объёме, в каком
удобно обучающемуся в данный момент.

Фреймворк максимально идеоматичен, т.е. строго подчиняется очень небольшому набору правил.

# Структура

| Папка  | Назначение          |
|--------|---------------------|
| server | Бэкенд (Express.js) | 
| client | Фронтенд (vue.js)   |
| common | Общий код           |

В качестве базы данных используется MongoDB.

    docker run --name jslearn -d -p 27017:27017 mongo:5.0.3

## Жизненый цикл
```
npm install    // установка
npm run serve  // hot-reload
npm run build  // сборка
npm run lint   // проверка кода

см. run.bat для возможности простого запуска в Windows
```
