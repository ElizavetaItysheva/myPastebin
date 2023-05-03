
## SkyPaste

____
### Разработчик
*Итышева Елизавета*

____
## Описание проекта и его функциональность

Сервис аналогичный pastebin.com — данный сервис позволяет заливать куски текста/кода ("пасту") и получать на них короткую ссылку, которую можно отправить другим людям.

____
## Реализованы следующие функции:

* Создание новой пасты
* Получение пасты по ссылке
* Получение последних 10 публичных паст
* Получение пасты по заголовку или тексту
* Автоматическое удаление устаревших паст

___
## Запуск приложения
* Для запуска приложения необходимо выполнить несколько шагов:
  - Клонировать проект и открыть его в среде разработки (например *IntelliJ IDEA*);
  - В файле **application.properties** указать путь к Вашей базе данных;
  - Запустить метод **main** в файле **MarketplaceApplication.java**.

После выполнения всех шагов, приложение будет доступно через swagger.
Swagger будет доступен по адресу: http://localhost:8080/swagger-ui/index.html

___
## Стэк технологий
* **Backend**:
    - Java 11
    - Maven
    - Spring Boot
    - Spring Web
    - Spring Data JPA
    - Stream API
    - REST
    - GIT
    - Swagger
    - Lombok
* **SQL**:
    - PostgreSQL
* **Test**:
    - Junit
    - Mockito
