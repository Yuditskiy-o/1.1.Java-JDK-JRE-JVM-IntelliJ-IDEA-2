# Отчёт о тестировании приложения Credit Card Number Validator

## Краткое описание

05.07.2020 - 05.07.2020 было проведено тестировании документации — руководства по установке IntelliJ IDEA и функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 2.5 часа

В результате тестирования выявлены следующие дефекты:
* https://github.com/Yuditskiy-o/1.1.Java-JDK-JRE-JVM-IntelliJ-IDEA-2/issues/1
* https://github.com/Yuditskiy-o/1.1.Java-JDK-JRE-JVM-IntelliJ-IDEA-2/issues/2
* https://github.com/Yuditskiy-o/1.1.Java-JDK-JRE-JVM-IntelliJ-IDEA-2/issues/3

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* https://docs.google.com/spreadsheets/d/1skLBuANAAbCk2NEl4wOFw7EvmTcp2iUy0rrABhR5ekY/edit#gid=0 — Чек-лист для проверки номеров карт разных платежных систем

В качестве тестовых данных использовались данные из репозитория [javaqa-homeworks/intro](https://github.com/netology-code/javaqa-homeworks/tree/master/intro), а также норме карта с сайта [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md — руководство позволяет корректно установить JetBrains Toolbox и IntelliJ IDEA, проблем не возникает (фактически — блокирующий установку баг после шага 3, см. прикрепленный ...issues/1);
* https://www.freeformatter.com/credit-card-number-generator-validator.html — приложение Credit Card Number Validator позволяет корректно обработать номера карт от всех брендов платежных систем (фактически — есть дефекты, см. прикрепленные ...issues/2 и ...issues/3).

Тестирование производилось в следующем окружении:
* **Устройство**: PC (Windows 7 Профессиональная SP1, x64)
* **Java**: openjdk version "11.0.7" 2020-04-14
* **Браузер**: Chrome (83.0.4103.116)
