# Отчет о тестировании Credit Card Number Validator

## Краткое описание
August 18 11:30 - August 18 11:51 было проведено функциональное тестирование Credit Card Number Validator

На тестирование затрачено 0,35 часа

В результате тестирования выявлены следующие дефекты:  

* [Номера карт длиннее 16 цифр не воспринимаются как валидные](https://github.com/pullulus/CreditCardNumberValidator/issues/1)
* [Номера карт короче 16 цифр не воспринимаются как валидные ](https://github.com/pullulus/CreditCardNumberValidator/issues/2)

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:
* [List of credit card number formats](https://www.freeformatter.com/credit-card-number-generator-validator.html)

В качестве тестовых данных использовались данные с сайта [FREEFORMATTER.COM](https://www.freeformatter.com/credit-card-number-generator-validator.html)

* VISA:

4024007115726456 - OK

4916514040743872622 - OK

* MasterCard:

5140045458423766 - OK

5360931102325817 - OK

* American Express (AMEX):

349195561572288 - OK

348270539416685 - OK

* Discover:

6011758077600085 - OK

6011564445985390653 - OK

* JCB:

3589457234985617 - OK

3536440722663446760 - OK

* Maestro:

5893334503824171 - OK

6759699772099916 - OK

* Diners Club - International:

36983642545904 - OK

36042212829105 - OK

* Visa Electron:

4917769926642889 - OK

4026710923611939 - OK

* InstaPayment:

6383981553684114 - OK

Windows 10 Домашняя 19041.450

Java 11.0.0

IntelliJ IDEA Community 2020.2