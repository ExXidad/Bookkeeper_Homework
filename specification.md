# Техническое задание

### Цель
Разработать простое приложение для контроля личных финансов
(ведение домашней бухгалтерии)

### Основное назначение приложения
Возможность записывать и анализировать расходы

### Ключевые особенности
- Open source
- Хранение данных у пользователя в виде БД SQLite (конфиденциальность и доступность)
- Максимально простой функционал (мы не ведем полноценную бухгалтерию)

### Функциональные требования
- Добавление, просмотр, редактирование и удаление категорий расходов
- Добавление, просмотр, редактирование и удаление записей о расходах
- Каждая запись о расходе относится к одной категории
- Отслеживание расходов за день/неделю/месяц
- Возможность ограничения бюджета на день/неделю/месяц

### Технические требования
- Интерпретатор Python 3.10
- Библиотека Pyside6 для реализации графического интерфейса
- Использование аннотаций типов и статический анализ с помощью `mypy`
- Тестирование с помощью `pytest`. Покрытие тестами не менее 75%. Приложите к своему коду отчет о тестировании в формате HTML
- Соответствие PEP8 (допустима длина строки до 90 символов). Проверка с помощью flake8
- Обязательное документирование всех классов и функций
- Оценка качества кода с помощью `pylint` не ниже 9
- Использование архитектурных паттернов с целью снижения связности кода и возможности расширить и изменить функциональность
- Специфических требований к производительности не предъявляется

### Финансирование и лицензирование
- Проект является некоммерческим
- Исходный код распространяется свободно под лицензией MIT
