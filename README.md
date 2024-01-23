Проект
============
Проект обновляется раз в год по расписанию и собирает debian пакет, содержащий все необходимое для работы d8

V8 JavaScript Движок
=============

V8 - это open source JavaScript движок от Google.

V8 может работать автономно, в c++ приложении или в браузере.

Документация: https://v8.dev/docs


Установка
=============

Список доступных пакетов можно найти на странице https://github.com/topvisor/v8js/releases в разделе "Assets"

Пример установки:

  wget https://github.com/topvisor/v8js/releases/download/v1.0.3/v8js.12.3.amd64.deb
  sudo dpkg -i v8js.12.3.amd64.deb

Пример использования:
  d8 <<< "console.log('hello world');"

Удаление
  dpkg -r v8js
