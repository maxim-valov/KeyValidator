# **Отчёт о тестировании приложения KeyValidator**

## **Краткое описание**
06 марта 2021 было проведено функциональное тестирование приложения KeyValidator при помощи положительного метода на основе [руководства](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D0%BA%D0%BB%D1%8E%D1%87%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B8) к приложению KeyValidator.

## **На тестирование затрачено**: 01 час

## **В результате тестирования выявлены следующие дефекты**:

* [Ряд валидных ключей опрделяются как невалидные в KeyValidator](https://github.com/maxim-valov/KeyValidator/issues/1#issue-823769506)
* [Ряд невалидных ключей определяется как валидные в KeyValidator](https://github.com/maxim-valov/KeyValidator/issues/2#issue-823771208)

## **Описание процесса тестирования**

**В процессе тестирования использовались следующие артефакты**:

Тестированиия проводился на осове требований к [Задаче 1](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-1---keyvalidator) из Домашнего задания к занатию «1.1. Введение в Java: JDK, JRE, JVM, IntelliJ IDEA»


**В качестве тестовых данных использовались данные**:

* [Инструкция по установке OpenJDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md) с ожидаемым результатом: OpenJDK загружается по указанной ссылке и устанавливается, что подтверждается введением в командной строке команды java -version
* [Руководство использования KeyValidator ](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)  c ожидаемым результатом: KeyValidator загружается по указанной ссылке, устанавливается и запускается в командной строке при помощи команды java KeyValidator
* [База тестовых валидных и невалидных ключей] (https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D0%BA%D0%BB%D1%8E%D1%87%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B8) c ожидаемым результатом: валидныым ключам присваивается значение ОК, невалидным - значение FAIL.


**Тестирование производилось в следующем окружении**:

* Windows 10x
* OpenJDK 11.0.10+9
* KeyValidator
* Git Bash