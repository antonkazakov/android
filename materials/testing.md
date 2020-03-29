---
layout: default
title: Testing
parent: Материалы к урокам
nav_order: 5
---

# Модуль #5. Testing
{: .no_toc }

## Список уроков
{: .no_toc .text-delta }

1. TOC
{:toc}

---

### Testing. Юнит-тесты и интеграционные тесты.
{: .text-gamma }

#### Книги
{: .no_toc }

- [Книга](https://www.manning.com/books/effective-unit-testing) с best practises по проектированию и написанию unit тестов
- [Книга](http://shop.oreilly.com/product/0636920038597) о том как пиcать тест на Spock. По своему опыту не рекомендую использовать Spock в связке с Robolectric, но если вы пишите не под Android, либо вам удалось избавиться от Robolectric, то советую посмотреть на Spock
- [Новое издание](https://www.manning.com/books/junit-in-action-third-edition) книги о написании тестов с JUnit 5

#### Статьи
{: .no_toc }

- [Памятка](http://wiki.c2.com/?ArrangeActAssert) по arrange-act-assert
- [Блог](https://testing.googleblog.com) от Google о тестировании. Много крутых постов о том как нужно писать тесты на Java/C++. Что выбрать DAMP или DRY, как правильно декомпозировать assertions и т.п. Советую перечитать все что уже есть в блоге и следить за новыми постами
- [Блог](https://martinfowler.com/testing/) Мартина Фаулера. Куча статей о том какие виды тестов существуют, какие тестовые дублеры и где нужно использовать, паттерны написания тестов и многое другое. Новые статьи почти не выходят, но то что уже написано прочитать нужно обязательно
- [Статья](https://docs.gradle.org/current/userguide/java_testing.html) о том как правильно выполнять тесты если вы используйте Gradle

#### Видео
{: .no_toc }

- [Крутой доклад](https://www.youtube.com/watch?v=EZ05e7EMOLM) про то как правильно готовить TDD
- [TDD в Android](https://www.youtube.com/watch?v=WW5TL7070xU)

---

### Testing. UI тесты на Espresso
{: .text-gamma }

#### Статьи
{: .no_toc}

- [Статья + пример](https://github.com/SeleniumHQ/selenium/wiki/PageObjects) реализации PageObject в Selenium. Мы не рассматриваем Selenium, но полезно почитать о том как реализовывать PageObject

#### Инструменты
{: .no_toc}

- [Репозиторий Barista](https://github.com/AdevintaSpain/Barista). Библиотека предоставляет более удобный API для написания Espresso тестов + механизм работы с flaky тестами
- [Репозиторий Kakao](https://github.com/agoda-com/Kakao) как пишут авторы "Nice and simple DSL for Espresso in Kotlin". Помимо удобного DSL из коробки предоставляют механизм интерсепторов. Их удобно использовать для встраивания в процесс выполнения теста
- [Репозиторий Kaspresso](https://github.com/KasperskyLab/Kaspresso). Kaspresso крутой фреймворк для UI-тестирования поверх Kakao. Помимо симпатичного DSL для написания тестов там есть обертка над UI Automator, ADB Server и интерсепторы для решения проблем с flaky тестами
- [Spoon](https://square.github.io/spoon/) - программа которая позволяет удобно управлять выполнением тестов на ферме. Неплохие отчеты, удобное api
- [Mockwebserver](https://github.com/square/okhttp/tree/master/mockwebserver) для OkHttp клиента и [дополнение](https://github.com/fabric8io/mockwebserver) для него которое предоставляет более удобный API. Используется для того чтобы мокать респонсы
#### Видео
{: .no_toc}

- [Единственное видео](https://www.youtube.com/watch?v=7lCsp84wVPM) которое я нашел на Youtube в котором разбирают что делает Espresso под капотом

#### Примеры
{: .no_toc}

- [Много сэмплов](https://github.com/android/testing-samples) по использованию Esrpesso для тестирования различных сценариев от Google

