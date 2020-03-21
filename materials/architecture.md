---
layout: default
title: Architecture
parent: Материалы к урокам
nav_order: 2
---

# Модуль #2. Architecture
{: .no_toc }

## Список уроков
{: .no_toc .text-delta }

1. TOC
{:toc}

---


### Design Patterns
{: .text-gamma }

TBD

---


### MVP + Clean Architecture
{: .text-gamma }

TBD

---


### MVVM + MVI
{: .text-gamma }

TBD

---


### RxJava
{: .text-gamma }

#### Документация
{: .no_toc }
- [Документация](https://github.com/ReactiveX/RxJava/wiki)

#### Книги
{: .no_toc }
- На мой взгляд, [Лучшая книга](https://www.amazon.com/Reactive-Programming-RxJava-Asynchronous-Applications/dp/1491931655) по RxJava. Написана для первой версии, но основные концепции, операторы почти не поменялись. Достаточно прочитать эту книгу и гайд по миграции на новую версию.
- [Дополнительная литература](https://github.com/ReactiveX/RxJava/wiki/Additional-Reading)

#### Видео
{: .no_toc }
- [Доклад](https://www.youtube.com/watch?v=htIXKI5gOQU) Джейка Вортон про RxJava 2 в контексте Android разработки
- Старые, но очень хорошие доклады [раз](https://www.youtube.com/watch?v=Eatfi4am0HU) и [два](https://www.youtube.com/watch?v=3jdvLrYZfB4&t),  которые знакомят с основами RxJava. Часть устарела, но общие положения все еще актуальны.

#### Статьи
{: .no_toc }
- [Хороший блог](https://blog.danlew.net/tag/rxjava/) в котором периодически появляются статьи про best practises по использованию RxJava

#### Практика
{: .no_toc }
- Задачки по RxJava на которых можно попрактиковаться и закрепить знания по операторам: [раз](https://github.com/senacor/rxjava-katas), [два](https://github.com/sergiiz/RxBasicsKata).


---

### Architecture Components
{: .text-gamma }

TBD

---


### Dagger 2
{: .text-gamma }

#### Документация
{: .no_toc }

- [Официальная документация](https://dagger.dev/users-guide)

#### Видео
{: .no_toc }

- [Крутой доклад](https://www.youtube.com/watch?v=oK_XtfXPkqw) от Gregory Kick из Google про то чем Dagger 2 отличается от Guice/Dagger, чем вдохновлялись авторы при создании Dagger 2 и как он работает внутри.
- [Хардкорный доклад](https://www.youtube.com/watch?v=wCvXe2LsN5o&t) от авторов библиотеки про то как Dagger 2 генерирует код. К сожалению, в видео проблемы со звуком, но в наушниках можно разобрать что говорят спикеры.
- [Доклад](https://www.youtube.com/watch?v=PBrhRvhF00k&t) от Ron Shapiro (*основной контрибьютор Dagger 2*) про Dagger Android.

#### Статьи
{: .no_toc }

- [Хороший Блог](https://mirekstanek.online/category/android/dagger-2/) со множеством статей про Dagger 2. Мне особенно зашла [статья](https://mirekstanek.online/dagger2metrics-measure-performance-of-di-graph-initialization/) про измерение перфоманса инициализации графа
- [Отличный цикл](https://habr.com/en/post/279125/) статей по знакомству с основными возможностями Dagger 2
- Некоторые [best practises](https://proandroiddev.com/dagger-2-on-android-the-official-guidelines-you-should-be-following-2607fd6c002e) по использованию Dagger 2
- [Статья](https://habr.com/en/company/yandex/blog/419295/) по правильному использованию Dagger 2 в многомодульном приложении. Есть множество подходов к построению многомодульного приложения и организации DI контейнеров в нем, но на мой взгляд, этот лучший

---


### Multimodule Project
{: .text-gamma }

#### Видео
{: .no_toc }

- [Отличный доклад](https://www.youtube.com/watch?v=pMEAD6jjbaI) про организацию многомодульного приложения и DI контейнера в нем
- Крайне полезный [доклад](https://www.youtube.com/watch?v=MGczcEukjEY) с AppsConf 2019 о способах ускорения сборки многомодульного проекта 
- [Один из первых докладов](https://www.youtube.com/watch?v=FMiFtsew2UY) о многомодульности в Android приложениях от Дениса Неклюдова

#### Статьи
{: .no_toc }

- [Фундаментальный труд](https://habr.com/en/company/kaspersky/blog/422555/) о многомодульном приложении и организации архитектуры в нем
- [Статья](https://medium.com/google-developer-experts/modularizing-android-applications-9e2d18f244a0) про многомодульность от GDE
- [Текстовая версия первого доклада](https://habr.com/en/company/yandex/blog/419295/)
- [Статья](https://jeroenmols.com/blog/2017/06/14/androidstudio3/) в которой сравниваются api и implementation

#### Примеры
{: .no_toc }

- [https://github.com/android/plaid](https://github.com/android/plaid)
- [https://github.com/chrisbanes/tivi](https://github.com/chrisbanes/tivi)
- [https://github.com/kotlinsg/modular](https://github.com/kotlinsg/modular)
- [https://github.com/Tagakov/modules-and-dagger](https://github.com/Tagakov/modules-and-dagger)


---

### Code smells & Refactoring
{: .text-gamma }

#### Книги
{: .no_toc }

- [Крутейшая книга](https://www.amazon.com/gp/product/0134757599?ie=UTF8&tag=martinfowlerc-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=0134757599) о рефакторинге кода. Подробно рассматриваются частые запахи кода, их влияние на проект и пути их устранения. Читать обязательно
- [Effective Java](https://www.oreilly.com/library/view/effective-java-3rd/9780134686097/). Эта книга обязательна к прочтению всем кто пишет на Java. 90 глав о том как нужно писать хороший код  
- [Effective Kotlin](https://leanpub.com/effectivekotlin/) аналог *Effective Java* про Kotlin.
- [Clean code](https://www.ozon.ru/context/detail/id/142429922/) от дядюшки Боба. Хорошая книга, но лично мне не нравится стиль написания. Слишком много воды, хорошо что есть [краткая выжимка](https://gist.github.com/wojteklu/73c6914cc446146b8b533c0988cf8d29) по основным идеям и правилам описанным в книге.

#### Видео
{: .no_toc }

- Два видео: [раз](https://www.youtube.com/watch?v=9S6qoFZiqCQ) и [два](https://www.youtube.com/watch?v=1a_tCXDivZ4) в котором спикер в режиме лайв-кодинга рефакторит огромные классы. Первое видео про C#, но методы рефакторинга применимы и в Java/Kotlin.







