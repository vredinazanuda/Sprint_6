# Sprint_6
Финальный проект 6 спринт

# Автоматизированные тесты для сайта по заказу самокатов

Этот проект содержит автоматизированные тесты для веб-приложения по заказу самокатов. Тесты написаны с использованием Python, Selenium WebDriver и фреймворка Pytest.

## Инструкции по запуску

1. Убедитесь, что у вас установлен Python и Mozilla Firefox.

2. Для запуска всех тестов выполните команду:

    ```
    pytest -v
    ```

3. Для получения отчета Allure выполните следующие команды:

    ```
    pytest --alluredir=allure_results
    allure serve allure_results
    ```

## Содержание проекта

- `locators/`: Папка с файлами, содержащими локаторы элементов на веб-страницах.
- `pages/`: Папка с файлами, содержащими классы страниц и их методы.
- `tests/`: Папка с файлами, содержащими тесты.
- `conftest.py`: Файл с фикстурами и общими настройками для тестов.
- `data.py`: Файл с тестовыми данными.
