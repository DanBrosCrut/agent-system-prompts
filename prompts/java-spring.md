# Java/Spring Boot Agent Instructions

## Стек
- Java 21 LTS
- Spring Boot 4.x
- Maven

## Правила
- Использовать @RestController для REST API
- Всегда добавлять javadoc к публичным методам
- Писать unit-тесты для сервисов
- Использовать constructor injection (не @Autowired на полях)

## Структура проекта
- controller/ — REST контроллеры
- service/ — бизнес-логика
- repository/ — доступ к данным
- dto/ — Data Transfer Objects
- config/ — конфигурация