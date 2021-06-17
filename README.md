# Отчёт о тестировании приложения бонусной системы

## Краткое описание

14.06.2021 - 14.06.2021 было проведено функциональное тестирование приложения бонусной системы.

На тестирование затрачено: 0.5 часов

В результате тестирования выявлены следующие дефекты:
* [Неверная итоговая сумма бонусов при внедрении дополнительного бонуса новым клиентам](https://github.com/ginnyboot/homework2.2precision/issues/1)
## Описание процесса тестирования

В процессе тестирования использовались следующие данные в качестве тестовых:
* Код с функционалом внедрения дополнительного бонуса новым клиентам:
```java
public class Main {
    public static void main(String[] args) {
        int balance = 2_000_000_000;
        int transfer = 500_000_000;
        int totalBalance = balance + transfer;
        System.out.println(totalBalance);
    }
}
```
Данные взяты из [текста домашнего задания](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)



Тестирование производилось в следующем окружении:
* Устройство: PC (Windows 10 Pro, x64)
* Java "11.0.11" 2021-04-20
* IntelliJ IDEA 2021.1.2 (Community Edition); Build #IC-211.7442.40, built on June 1, 2021
