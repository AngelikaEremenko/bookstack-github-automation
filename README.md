# GitHub → BookStack Automation

Проект автоматизации создания страниц в BookStack на основе GitHub Issues.

## Возможности

* создание Issue по шаблону;
* автоматический запуск GitHub Actions;
* преобразование содержимого Issue в HTML;
* публикация страницы через BookStack API;
* использование GitHub Secrets для безопасного хранения токенов.

## Технологии

* GitHub Actions
* YAML
* Node.js
* REST API
* BookStack API

## Сценарий работы

1. Пользователь создаёт GitHub Issue по шаблону.
2. GitHub Actions запускает workflow.
3. Содержимое Issue преобразуется в HTML.
4. Через BookStack API создаётся новая страница в базе знаний.

## Использование

Для работы необходимо настроить:

* BOOKSTACK_API_ID
* BOOKSTACK_API_SECRET
* BOOKSTACK_URL
* BOOKSTACK_BOOK_ID

в разделе GitHub Secrets.
