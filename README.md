# Домашнее задание к занятию «7.5. Puppeteer 2»

## Решения
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.5/puppeteer-2/net.test.js">net.test.js</a>. - Автотесты.
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/tree/main/7.5/puppeteer-2/features">puppeteer-2/features</a>. - Репозиторий с тестовыми сценариями и шагами Cucumber.

<a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/tree/main/7.5/puppeteer-2">Репозиторий</a> с проектом (Jest + Cucumber + Puppeteer).

## Что было сделано
* В <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.5/puppeteer-2/package.json">package.json</a> - Дописан скрипт запуска Jest, Cucumber. Добавлены зависимости Puppeteer, Chai, Jest, Cucumber, Jest-Puppeteer.
* Создан <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.5/puppeteer-2/jest.config.js">jest.config.js</a> c настройками об используемых библиотеках и тайм-аутом.
* Создан <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.5/puppeteer-2/jest-puppeteer.config.js">jest-puppeteer.config.js</a> с дополнительными настройками puppeteer.
* Создан служебный класс с асинхронными методами взаимодействия с элементами страниц, либо генерирующие исключение - <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.5/puppeteer-2/lib/commands.js">commands.js</a>.
* Написаны автотесты бронирования билетов - <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.5/puppeteer-2/net.test.js">net.test.js</a>.
* Описаны тестовые сценарии - <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.5/puppeteer-2/features/first.feature">first.feature</a>
и реализовано их выполнение - <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.5/puppeteer-2/features/step_definitions/first.step.js">first.step.js</a>, с использованием Cucumber.


## Описание Задания 1. Puppeteer. Бронирование билетов

1. Познакомьтесь с [приложением для тестирования](http://qamid.tmweb.ru/client/index.php).  
2. Создайте новый проект с использованием Puppeteer.
3. Напишите тест-сьют из трёх тест-кейсов для бронирования билетов. 2 happy path теста и 1 — sad path.
4. Автоматизируйте эти тест-кейсы, используя полученные на лекциях знания, в том числе, hooks, custom commands.

Для выполнения задания не забывайте отталкиваться от подходов DRY, AAA (Act, Assign, Assert) или Given-When-Then.

## Описание Задания 2. Puppeteer & Cucumber

1. Подключите Cucumber к проекту.
2. Организуейте BDD подход для ваших тестов.
3. Запушьте репозиторий — изменения для двух задач — и сдайте ссылку на проверку.
