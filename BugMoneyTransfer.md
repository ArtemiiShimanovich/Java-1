# Отчёт о тестировании Money Transfer

## Краткое описание

11/09/2021 - 11/09/2021 было проведено компонентное позитивное тестирование приложения Money Transfer

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [BugMoneyTransfer](https://github.com/ArtemiiShimanovich/Java-1/issues/1)


## Описание процесса тестирования

В качестве тестовых данных использовались данные 
* [Задание 1](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0)
* текущий баланс счёта клиента - переменная типа int, значение int current = 2_000_000_000 (два миллиарда рублей);
* сумма перевода - переменная типа int, значение int transfer = 500_000_000 (пятьсот миллионов рублей);
* переменная для хранения итогового значения - тип int total.
* Ожидаемый результат: 2_500_000_000.

Тестирование производилось в следующем окружении:
* ОС windows 10 версия 2004, 19041.1165 64 бит
* Версия Java 11
    openjdk version "11.0.11" 2021-04-20
    OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9)
    OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)
* Chrome browser Версия 92.0.4515.159 (Официальная сборка), (64 бит)