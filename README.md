# Lab-work-5 #

## Общие задания: ##

### 1. ### 
##### Модифицировать код индивидуального задания 1 лабораторной работы №1.Организовать хранение данных в виде массива структур с полями, которые соответствуют столбцам таблицы. Консольное приложение должно быть интерактивным и постоянно предлагать на выбор одно из следующих действий, пока пользователь не введет 7, т.е. выберет пункт «7 – Выход»: #####
#### ... ####
##### 1 – Просмотр таблицы #####
##### 2 – Добавить запись #####
##### 3 – Удалить запись #####
##### 4 – Обновить запись #####
##### 5 – Поиск записей #####
##### 6 – Просмотреть лог #####
##### 7 – Выход #####
#### ... ####
##### При выборе пункта «Просмотр таблицы» программа должна отобразить таблицу со всеми записями, по аналогии с лабораторной работой №1. При выборе пункта «Добавить запись» программа должнапоследовательно предложить заполнить все поля новой записи и добавить ее в конец набора. При выборе пункта «Удалить запись» программа должнапредложить пользователю ввести номер записи, которую необходимо удалить. Удаление из массива подразумеваетуменьшение числа элементов на 1 исмещение всех записей, находящихся после удаляемой, на 1 влево в массиве. При выборе пункта «Обновить запись» программа должна предложить пользователю ввести номер записи, которую необходимо обновить; затем предложить ввести новые значения всех полей этой записи и обновить ее. При выборе пункта «Поиск записей» программа должна предложить ввести пользователю фильтр для поиска (выберите любой фильтр или спросите у проработчика. Например, найти всех сотрудников с годом рождения больше 1985) и вывести результаты, соответствующие фильтру внутри таблицы того же вида. При выборе пункта «Просмотреть лог» должен быть отображен лог действий пользователя (см. следующий пункт). #####

### 2. ###
##### Все действия пользователя (добавление / удаление / обновление записей) должны фиксироваться в специальном логе. Лог представляет собой тоже массив структур-записей (максимум 50 последних действий) с информацией о перечисляемом типе операции (ADD, DELETE, UPDATE), точном времениоперации и сведениямио записи, с которой было произведено действие. Вывод на консоль должен иметь вид:
#### ... ####
##### 12:45:02 – Добавлена запись “Иванов” #####
##### 12:46:25 – Добавлена запись “Петров” #####
##### 12:46:58 – Удалена запись “Иванов” #####
#### ... ####
##### Ниже через одну пустую строку нужно также вывестивремя самого долгого «простоя» в текущем сеансе: #####
#### ... ####
##### 00:01:23 – Самый долгий период бездействия пользователя #####
#### ... ####

## Контрольные вопросы: ##
#### ... ####
##### 1. Какие возможности предоставляет C#.NET для работы с датой и временем? #####
##### 2. Опишите особенности перечисляемого типа enum в C#.NET. #####
##### 3. Чем удобны структуры? Особенности типа struct. #####
##### 4. Созданиеи доступ к членам структуры. #####
#### ... ####