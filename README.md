# onec-server-k8s

Инстанс сервера 1С:Предприятия предназначенный для запуска внутри кластера Kubernates

## Особенности

1. Включает в сбея [утилиту](https://github.com/v8platform/onec-util) для работы с 1С:Предприятие

## Сборка 

1. Создать файл `.env` в корне проекта. В качестве примера использовать `.env.example`. В файле должны быть определены переменные:
```
    ONEC_USERNAME=<ПОЛЬЗОВАТЕЛЬ_USERS.1C.V8.RU>
    ONEC_PASSWORD=<ПАРОЛЬ_ОТ_USERS.1C.V8.RU>
    ONEC_VERSION=8.3.14.199
    VERSION_ONEC_UTIL=0.1.2

```
2. Запустить сборку образа с помощью скрипта

```
    ./make.sh
```
