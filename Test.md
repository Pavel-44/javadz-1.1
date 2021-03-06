<h1>Тест-план. Тестирование функциональности валидации номера банковской карты</h1> 

<h2>Тест-кейс 1</h2>

*Ввод номера банковской карты Visa*

**<h3>Описание (Summary)</h3>**
*Проверяется работа функциональности по валидации банковской карты Visa*

**<h3>Приоритет (Priority)</h3>**
*High*

**<h3>Шаги (Steps to reproduce):</h3>**
1. *Запуститить Intellij IDEA Community*
1. *Вставить номер карты 4016040420736472 в четвертую строку кода, заменив имеющееся значение между двумя ковычками*
1. *Запустить программу нажав на кнопку Run*

**<h3>Ожидаемый результат (Expected result):</h3>**
*Номер карты валидный, ответ программы Ok*

<h2>Тест-кейс 2</h2>

*Ввод номера банковской карты MasterCard*

**<h3>Описание (Summary)</h3>**
*Проверяется работа функциональности по валидации банковской карты MasterCard*

**<h3>Приоритет (Priority)</h3>**
*High*

**<h3>Шаги (Steps to reproduce):</h3>**
1. *Запуститить Intellij IDEA Community*
1. *Вставить номер карты 5340005193001077 в четвертую строку кода, заменив имеющееся значение между двумя ковычками*
1. *Запустить программу нажав на кнопку Run*

**<h3>Ожидаемый результат (Expected result):</h3>**
*Номер карты валидный, ответ программы Ok*

<h2>Тест-кейс 3</h2>

**<h3>Название (Title)</h3>**
*Работа приложения при вводе номера банковской карты из 14 цифр*

**<h3>Описание (Summary)</h3>**
*Проверяется работа функциональности по валидации банковской карты при вводе банковской карты, состоящей из 14 цифр*

**<h3>Приоритет (Priority)</h3>**
*Low*

**<h3>Шаги (Steps to reproduce):</h3>**
1. *Запуститить Intellij IDEA Community*
1. *Вставить номер карты 30535413549527 в четвертую строку кода, заменив имеющееся значение между двумя ковычками*
1. *Запустить программу нажав на кнопку Run*

**<h3>Ожидаемый результат (Expected result):</h3>**
*Номер карты валидный, ответ программы Ok*

<h2>Тест-кейс 4</h2>

**<h3>Название (Title)</h3>**
*Работа приложения при вводе номера банковской карты из 19 цифр*

**<h3>Описание (Summary)</h3>**
*Проверяется работа функциональности по валидации банковской карты при вводе банковской карты, состоящей из 19 цифр*

**<h3>Приоритет (Priority)</h3>**
*Low*

**<h3>Шаги (Steps to reproduce):</h3>**
1. *Запуститить Intellij IDEA Community*
1. *Вставить номер карты 3545643560291685433 в четвертую строку кода, заменив имеющееся значение между двумя ковычками*
1. *Запустить программу нажав на кнопку Run*

**<h3>Ожидаемый результат (Expected result):</h3>**
*Номер карты валидный, ответ программы Ok*

<h2>Тест-кейс 5</h2>

**<h3>Название (Title)</h3>**
*Работа приложения при вводе пустого значения в номер банковской карты*

**<h3>Описание (Summary)</h3>**
*Проверяется работа функциональности по валидации банковской карты при отправке пустого значения в номере карты*

**<h3>Приоритет (Priority)</h3>**
*Medium*

**<h3>Шаги (Steps to reproduce):</h3>**
1. *Запуститить Intellij IDEA Community*
1. *В четвертой строке кода удалить имеющиеся значения, чтобы между двумя ковычками был пробел*
1. *Запустить программу нажав на кнопку Run*

**<h3>Ожидаемый результат (Expected result):</h3>**
*Номер карты невалидный, ответ программы Fail*

<h2>Тест-кейс 6</h2>

**<h3>Название (Title)</h3>**
*Работа приложения при вводе буквенного значения в номер банковской карты*

**<h3>Описание (Summary)</h3>**
*Проверяется работа функциональности по валидации банковской карты при отправке буквенного значения в номере карты*

**<h3>Приоритет (Priority)</h3>**
*Medium*

**<h3>Шаги (Steps to reproduce):</h3>**
1. *Запуститить Intellij IDEA Community*
1. *В четвертой строке кода между двумя ковычками ввести произвольный набор буквенных символов*
1. *Запустить программу нажав на кнопку Run*

**<h3>Ожидаемый результат (Expected result):</h3>**
*Номер карты невалидный, ответ программы Fail*

<h2>Тест-кейс 7</h2>

**<h3>Название (Title)</h3>**
*Работа приложения при вводе произвольного набора из 16 цифр в номер банковской карты*

**<h3>Описание (Summary)</h3>**
*Проверяется работа функциональности по валидации банковской карты при вводе вместо номера банковской карты произвольного набора цифр*

**<h3>Приоритет (Priority)</h3>**
*Medium*

**<h3>Шаги (Steps to reproduce):</h3>**
1. *Запуститить Intellij IDEA Community, если не запущена*
1. *В четвертую строку кода, заменив имеющееся значение между двумя ковычками, ввести произвольный набор цифр*
1. *Ззапустить программу нажав на кнопку Run*

**<h3>Ожидаемый результат (Expected result):</h3>**
*Номер карты невалидный, ответ программы Fail*


