<h1 align="center">
  <a href="https://www.npmjs.com/package/bomber-api"><img src="https://img.shields.io/npm/dt/bomber-api" alt="NPM downloads"></a>
  <br>
  <a href="https://github.com/shketov/bomber-api"><img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/apple/237/collision-symbol_1f4a5.png"></a>
  <br>
  bomber-api
  <br>
</h1>

<h4 align="center">Удобное API для создания собственного SMS бомбера</h4>


## Установка

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/b389dba0709d4604a05a164b319fb5aa)](https://app.codacy.com/gh/shketov/bomber-api?utm_source=github.com&utm_medium=referral&utm_content=shketov/bomber-api&utm_campaign=Badge_Grade)

`npm install bomber-api`

`const bomber = require("bomber-api")`

## Как использовать?

Иницилизация атаки - `attack(number, loop)`
  * number - номер телефона
  * loop - число повторов цикла

Например: `bomber.attack(79999999999, 5)`

Остановить атаку - `stop(number)`
  * number - номер телефона
  
Например: `bomber.stop(79999999999)`

Активные атаки - `list()`
  * Не принимает параментров, возвращает список активных атак в JSON массиве

## TODO:
  * Больше сервисов
  * ~~Остановка атаки~~
  * Поддержка Proxy
  * Лог отправки сообщений
  * ~~Поддержка нескольких атак одновременно~~
  * ~~Отправка SMS по доступным странам~~


