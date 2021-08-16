## Краткое описание

14.08.2021 было проведено функциональное тестирование методом белого ящика приложения Precision

На тестирование затрачено: 40 минут

В результате выявлены следующие дефекты:
[Некорректно выполняется расчет итогового бонуса](https://github.com/evgenijstr/java1.2.2Precision/issues/1)

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:
* [тест-кейс](https://docs.google.com/spreadsheets/d/1e9eY1GGlccvK1I99BbMqwzSu1cbZojpifHM_Y24DYnQ/edit?usp=sharing)
* [образец кода](https://github.com/evgenijstr/java1.2.2Precision/blob/master/src/code.txt)


В качестве тестовых данных использовались следующие контейнеры и переменные
* double regularBonus = 0.3
* double specialBonus = 0.6
* double totalBonus = regularBonus + specialBonus


Тестирование проводилось в следующем окружении
* Ubuntu 20.04.2 LTS, 64 bit
* Java 11.0.11
* IntelliJ IDEA 2021.2 (Community Edition) Build #IC-212.4746.92
* IntelliJ IDEA 2021.2 (Community Edition) Build #IC-212.4746.92