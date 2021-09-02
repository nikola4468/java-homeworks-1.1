# Отчёт о тестировании KardValidator.

## Проверка функциональности валидации номера банковской карты различных систем.

<31.08.2021> - <31.08.2021> было проведено функциональное тестирование приложения валидации номера банковской карты.

На тестирование затрачено: 2 часа

### В результате тестирования выявлены следующие дефекты:
* [Не валидируется VISA с 19-ти значным номером карты](https://github.com/nikola4468/java-homeworks-1.1/issues/1)
* [Не валидируется American Express с 15-ти значным номером карты](https://github.com/nikola4468/java-homeworks-1.1/issues/2)
* [Не валидируется JCB с 19-ти значным номером карты](https://github.com/nikola4468/java-homeworks-1.1/issues/3)

## Описание процесса тестирования

### В процессе тестирования использовались следующие артефакты:
* Список с номерами карт разных систем, взятый с [сайта](https://www.freeformatter.com/credit-card-number-generator-validator.html)
* Руководство из [домашнего задания](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)

###В качестве тестовых данных использовались данные с [сайта](https://www.freeformatter.com/credit-card-number-generator-validator.html)
* VISA:

4532963447230242 ok

4716601108107113 ok

4024007133549821443 ok

* MasterCard:

5198977209136613 ok

5145324900706507 ok

5321977617971999 ok


* American Express (AMEX):

346896705421430 ok

349978611806651 ok

340718904993009 ok

* Discover:

6011165289438199 ok

6011602566240245 ok

6011849481415411907 ok

* JCB:

3530321623343483 ok

3543057137161269 ok

3528243214977271155 ok

* Diners Club - North America:

5493711604635685 ok

5562500322024637 ok

5421799835170025 ok

* Diners Club - Carte Blanche:

30434900519740 ok

30279536420908 ok

30010940996385 ok

* Diners Club - International:

36932929067819 ok

36205860948788 ok

36622369850291 ok

* Maestro:

0604353389415202 ok

5020177925117849 ok

0604219687600094 ok

* Visa Electron:

4026925944790971 ok

4917184539179511 ok

4913327354367968 ok

* InstaPayment:

6376407195390281 ok

6387279839935798 ok

6388326498018322 ok

### Тестирование производилось в следующем окружении:
* macOS 11.5.2 (20G95),
* IntelliJ IDEA 2021.2.1 (Community Edition)

  Build #IC-212.5080.55, built on August 24, 2021

  Runtime version: 11.0.11+9-b1504.16 x86_64

  VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
