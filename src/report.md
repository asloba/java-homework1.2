# Отчёт о тестировании валидатора банковских карт
## Краткое описание
04.03.2020 было проведено функциональное тестирование кода, проверяющего валидацию банковских карт из [Задачи 2](https://github.com/netology-code/javaqa-homeworks/tree/master/intro).

На тестирование затрачено: 1,5 часа

В результате тестирования выявлены следующие дефекты:

* [Баг-репорт №1](https://github.com/asloba/java-homework1.2/issues/1)

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:

- [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
- [Баг-репорт №1](https://github.com/asloba/java-homework1.2/issues/1)


В качестве тестовых данных использовались данные из [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html):

- 349912728934452
- 4485033178182090302
- 30095805428301

Тестирование производилось в следующем окружении:

- Windows 10 Pro. 64-разрядная операционная система, процессор х64
- Openjdk version "11.0.10"