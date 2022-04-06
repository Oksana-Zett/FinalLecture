# План автоматизации тестирования сценария перехода к форме записи и заполнения этой формы #

## 1. Перечень автоматизируемых сценариев ##

1.1. Тест-сьют: Возможность перехода с главной страницы на страницу профессии "Тестировщик ПО"

Тест-кейсы:
* Переход через "Каталог курсов" - раздел "Программирование"- раздел "Тестировщик ПО" https://prnt.sc/WIIB7JqPJACW
* Переход через раздел "Программирование" https://prnt.sc/5xTF9KjeUS6c - раздел "Тестировщик ПО" https://prnt.sc/sDNG5gNupl47
* Переход через гиперссылку "Выбрать курс" https://prnt.sc/_tKE5BVsX0bx - Ввод в поисковую строку значения "Тестировщик ПО" https://prnt.sc/fWJmMt-C0rrG
* Переход через гиперссылку "Выбрать курс" https://prnt.sc/_tKE5BVsX0bx - Выбор направления "Программирование" https://prnt.sc/4MVLlHJFr4au - Выбор из списка "Тестировщик ПО"
* Переход через раздел "Каталог" в футере главной страницы https://prnt.sc/rKnUhPB_5gVk - Ввод в поисковую строку значения "Тестировщик ПО" https://prnt.sc/fWJmMt-C0rrG
* Переход через раздел "Каталог" в футере главной страницы https://prnt.sc/rKnUhPB_5gVk -  Выбор направления "Программирование" https://prnt.sc/4MVLlHJFr4au - Выбор из списка "Тестировщик ПО"
* Переход через раздел "Популярные курсы" в футере главной страницы https://prnt.sc/pu46sWbzmAeP  -  Ввод в поисковую строку значения "Тестировщик ПО" https://prnt.sc/fWJmMt-C0rrG
* Переход через раздел "Популярные курсы" в футере главной страницы https://prnt.sc/pu46sWbzmAeP  -  Выбор направления "Программирование" https://prnt.sc/4MVLlHJFr4au - Выбор из списка "Тестировщик ПО"


1.2.  Тест-сьют: Возможность перехода со страницы профессии "Тестировщик ПО" на форму записи на обучение профессии

Тест-кейсы:

* Пролистать всю страницу профессии до формы записи https://prnt.sc/n4uy9NLqT5ZQ
* Кликнуть на кнопку "Записаться" в начале страницы https://prnt.sc/uW1dErK0ZwLe
* Кликнуть на кнопку "Записаться", появившуюся в верхнем правом углу страницы, при пролистывании страницы вниз https://prnt.sc/AzTJNh6xbD0M

1.3. Тест-сьют: Заполнение формы записи на обучение профессии "Тестировщик ПО"

Тест-кейсы:

* Ввод допустимых значений в поле "Имя" (позитивные и негативные проверки)
* Ввод граничных значений в поле "Имя" (позитивные и негативные проверки)
* Ввод допустимых значений в поле "Телефон" (позитивные и негативные проверки)
* Ввод граничных значений в поле "Телефон" (позитивные и негативные проверки)

## 2. Перечень используемых инструментов с обоснованием выбора ##

1. Язык программирования Java - один из самых востребованных языков на рынке в сфере автоматизации тестирования, обладающий рядом преимуществ:
* простота/логичность синтаксиса;
* использование принципов ООП (абстракция, инкапсуляция, наследование, полиморфизм);
* безопасность;
* производительность;
* надежность;
* независимость от аппаратной части и ОС
2. IntelliJ IDEA - одна из самых распространенных и мне хорошо известных сред разработки ПО на Java, в том числе для автоматизированных тестов
3. Git - инструмент для реализации распределенной системы контроля версий
4. GitHub - крупнейший веб-сервис для хранения и синхронизации кода, главной целью которого является поддержка совместной разработки проектов
5. AppVeyor - распределенный веб-сервис непрерывной интеграции, предназначенный для сборки и тестирования ПО, расположенного на GitHub
6. DevTools (вкладка Elements) - для просмотра и выбора селекторов, и написания автотестов с их применением
7. Gradle - система автоматической сборки проектов на основе описания их структуры
8. Lombok - библиотека для сокращения кода в классах и расширения функциональности языка Java
9. Selenide - фреймворк, упрощающий написание автотестов для работы с веб-страницами
10. JUnit5 - фреймворк для модульного тестирования ПО на языке Java
11. Faker - библиотека для генерации данных для автотестов

## 3. Перечень необходимых разрешений/данных/доступов ##

1. Разрешение на проведение автоматизированного тестирования
1. Разрешение на доступ к требованиям
1. Разрешение на применение инструментов из п.2 Плана
1. Доступ к БД
1. Доступ к API для реализации запросов

## 4. Перечень и описание возможных рисков при автоматизации ##

1. Написание автотестов на функции, выполняемые на разовой основе, влекут за собой финансовые и временные потери
1. Если неверно выбрать инструмент для тестирования, можно попасть в зависимость от технологий и специалистов (нужно грамотно подходить к выбору инструментов с точки зрения их известности и стоимости)
1. Применение автоматизированного тестирования на функционал, который не был проверен вручную, также влечет финансовые и временные потери, а также существует риск выпуска на продакшн продукта с некорректно работающей функциональностью

## 5. Перечень необходимых специалистов для автоматизации ##

1. Автоматизированный тестировщик (QA Automation Engineer)
1. Lead QA

## 6. Интервальная оценка с учётом рисков (в часах) ##

1. Тестирование перехода на страницу профессии (см. п.1, пп.1.1): 4ч
1. Тестирование перехода на форму записи на обучение профессии (см. п.1, пп.1.2): 4ч
1. Тестирование формы записи на обучение профессии (см. п.1, пп.1.3): 4ч
