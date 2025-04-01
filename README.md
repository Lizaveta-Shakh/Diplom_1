## Дипломный проект. Задание 1: Юнит-тесты

### Автотесты для проверки программы, которая помогает заказать бургер в Stellar Burgers

### Реализованные сценарии

Созданы юнит-тесты, покрывающие классы `Bun`, `Burger`, `Ingredient`, `Database`

Процент покрытия 100% (отчет: `htmlcov/index.html`)

### Структура проекта

- 'helpers' - содержит файл data с тестовыми данными, необходимыми для проведения тестов
- `tests` - пакет, содержащий тесты, разделенные по классам: test_bun, test_Burger, test_Database, test_ingredient
- файл conftest содержит моки, вынесенные в фикстуры
### Запуск автотестов

> 'pytest -v'

**Установка зависимостей**

> `$ pip install -r requirements.txt`

**Запуск автотестов и создание HTML-отчета о покрытии**

>  `$ pytest --cov=source_code.bun --cov=source_code.ingredient --cov=source_code.burger --cov=source_code.database --cov-report=html`
