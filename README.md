# AlorApiR
Набросок клиента к Alor Open API брокера АЛОР

## Состав
Клиентское приложение состоит из клиента для JSON Open API (RpcClient.R) и клиента для Websockets с примером подписки на данные (обезличенные сделки по инструменту). Обработчики входящих данные делайте по своему усмотрению. В примерах кода осуществляется преобразование дат в UNIX Timestamp. Так как к теме проекта это отношения не имеет, методы преобразования в проекте не содержатся

### Known issues и особенности реализации
В проекте отсутствует обработка ошибок соединения и ошибок парсинга данных, отсутствуют проверки на допустимость вводимых в запросы данных. Имейте в виду.
