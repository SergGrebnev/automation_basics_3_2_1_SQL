[![Java CI with Gradle](https://github.com/SergGrebnev/automation_basics_3_2_1_SQL/actions/workflows/gradle.yml/badge.svg)](https://github.com/SergGrebnev/automation_basics_3_2_1_SQL/actions/workflows/gradle.yml)

## Установка сервера MySQL

*(ОС: Linux Mint)*

1. Установить и запустить приложение `DBeaver` 
2. Создать соединение с параметрами:
    * URL: jdbc:mysql://localhost:3306/db
    * Сервер: localhost
    * Порт: 3306
    * База данных: db
    * Пользователь: user
    * Пароль: pass
3. Запустить файл app-deadline.jar командой 
    `java -jar app-deadline.jar -P:jdbc.url=jdbc:mysql://localhost:3306/db -P:jdbc.user=user -P:jdbc.password=pass`
