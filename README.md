# Отчёт о тестировании KeyValidator 

## Краткое описание

25.09.2020 - 25.09.2020 было проведено тестирование документации, установки и функциональное тестирование 

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Скриншоты в инструкции по установке OpenJDK содержат указание на старую версию](https://github.com/GrebenkovaMaria/HW_JavaForQA_1.1/issues/1)
* [в инструкции по установке OpenJDK для Windows отсутствует финальный шаг по указанию пути в командной строке до файлов JDK](https://github.com/GrebenkovaMaria/HW_JavaForQA_1.1/issues/2)
* [отсутсвует шаг в инструкции для использования приложения KeyValidator](https://github.com/GrebenkovaMaria/HW_JavaForQA_1.1/issues/3)
* [KeyValidator некорректно отображает результат по некоторым ключам](https://github.com/GrebenkovaMaria/HW_JavaForQA_1.1/issues/4) 

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [инструкция по установке JDK на Windows](https://github.com/GrebenkovaMaria/HW_JavaForQA_1.1/blob/master/openjdk11-manual.md)
* [руководство использования KeyValidator](https://github.com/GrebenkovaMaria/HW_JavaForQA_1.1/blob/master/user-manual.md)
* валидные и невалидные ключи, предстваленные в [руководстве использования](https://github.com/GrebenkovaMaria/HW_JavaForQA_1.1/blob/master/user-manual.md)


В качестве тестовых данных использовались данные:
* ключи для проверки валидации представленные в [руководстве использования](https://github.com/GrebenkovaMaria/HW_JavaForQA_1.1/blob/master/user-manual.md);


Тестирование производилось в следующем окружении:
* Windows 10
* Open JDK11
