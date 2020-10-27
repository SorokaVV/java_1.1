# Отчет об установке Java и тестировании KeyValidator
Дата начала 27.10.2020.
Дата окончания 27.10.2020.
На тестирование затрачено 45 минут. Использовалось функциональное тестирование.
### В результате тестирования ключей были выявлены следующие дефекты:
1. [Ошибка при вводе валидных ключей KeyValidator](https://github.com/SorokaVV/java_1.1/issues/1)
1. [Ошибка при вводе невалидных ключей KeyValidator](https://github.com/SorokaVV/java_1.1/issues/2)
### Тест кейс AA-1
#### Установка Java JDK 11

1. Скачать и установить Java по [ссылке](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
1. Проверить в терминале установку и версию java.

Ожидаемый результат
* openjdk version "11.0.9" 2020-10-20
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9+11)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9+11, mixed mode)


Фактический результат
* openjdk version "11.0.9" 2020-10-20
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9+11)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9+11, mixed mode)

### Тест кейс АA-2
 #### Проверка валидных ключей в программе KeyValidator

1. Скачать файл [keyvalidator.class](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class)
1. Открыть git bush из папки,куда был скачан файл
1. Проверить валидные ключи командой java KeyValidator
#### Ожидаемый результат
* Статус OK при проверке всех ключей
#### Фактический результат
* 2 ключа показывают статус Fail
### Тест кейс AA-3
#### Проверка невалидных ключей в программе KeyValidator
1.  Скачать файл [keyvalidator.class](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class)
1. Открыть git bush из папки,куда был скачан файл
1. Проверить валидные ключи командой java KeyValidator
#### Ожидаемый результат
* Статус FAIL при проверке всех ключей
#### Фактический результат
* Один ключ показывает стаус Ок

### Окружение
* Win10 x64
* Java 11.00.9
