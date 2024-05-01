# Домашнее задание к занятию «7.5. Puppeteer 2»

## Решения
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/tree/a34f0c1fac66d7ae133fba25690391c0a6d5eb35/7.5/puppeteer-2">Репозиторий</a> с Jest + Cucumber + Puppeteer проектом.
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/a34f0c1fac66d7ae133fba25690391c0a6d5eb35/7.5/puppeteer-2/net.test.js">net.test.js</a>. - Автотесты.
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/tree/a34f0c1fac66d7ae133fba25690391c0a6d5eb35/7.5/puppeteer-2/features">puppeteer-2/features</a>. - Репозиторий с тестовыми сценариями и шагами Cucumber.

## Что было сделано
* В package.json - Дописан скрипт запуска Jest, Cucumber. Добавлены зависимости Puppeteer, Chai, Jest, Cucumber, Jest-Puppeteer.
* Создан jest.config.js c настройками об используемых библиотеках и тайм-аутом.
* Создан jest-puppeteer.config.js с дополнительными настройками puppeteer.
* Создан служебный класс с асинхронными методами взаимодействия с элементами страниц, либо генерирующие ошибку - commands.js
* Написаны автотесты бронирования билетов - net.test.js.
* Описаны тестовые сценарии - first.feature и реализовано их выполнение - first.step.js, с использованием Cucumber.


## Задача 1. Puppeteer. Бронирование билетов

1. Познакомьтесь с [приложением для тестирования](http://qamid.tmweb.ru/client/index.php).  
2. Создайте новый проект с использованием Puppeteer.
3. Напишите тест-сьют из трёх тест-кейсов для бронирования билетов. 2 happy path теста и 1 — sad path.
4. Автоматизируйте эти тест-кейсы, используя полученные на лекциях знания, в том числе, hooks, custom commands.

Для выполнения задания не забывайте отталкиваться от подходов DRY, AAA (Act, Assign, Assert) или Given-When-Then.

## Задача 2. Puppeteer & Cucumber

1. Подключите Cucumber к проекту.
2. Организуейте BDD подход для ваших тестов.
3. Запушьте репозиторий — изменения для двух задач — и сдайте ссылку на проверку.
