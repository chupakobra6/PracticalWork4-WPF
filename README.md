# Практическая 4 - Учет бюджета
Необходимо в приложении WPF реализовать приложение по учету своего бюджета

Необходимый функционал:
- После запуска программы должны быть отображены все записи на сегодняшнюю дату
- Записи должны отображаться в табличном виде
- Должен быть выбор записей по дате. При изменении даты, таблица меняется и отображаются только записи на эту дату
- Должны быть текстовые поля для всех данных записей, кроме даты и типа записи
- Тип записи должен быть в виде выпадающего списка
- Должна быть возможность добавить новый тип записи. Для добавления нового типа должно появляться новое окно с вводом названия
- Если человек подтвердил создание нового типа записи, он сохраняется. Если я закрыла окно - тип не сохраняется. После сохранения записи список с типом записи обновляется
- При выборе записи из таблицы, ее данные должны отобразиться в текстовых полях и списках
- Должен быть функционал добавления новой записи в таблицу
- Если человек вводит отрицательную сумму, она должна записаться как вычет денег. Если он вводит положительную - поступление денег
- Сумма денег в таблице должна быть только положительной, все отрицательные значения записываются как вычет, но все равно само количество денег показывается без минуса
- Должен быть функционал изменения существующей записи из таблицы
- Должен быть функционал удаления существующей записи из таблицы
- Должен показываться суммарный итог за все время
- Данные о записях и типе записей должны сохраняться после закрытия приложения и загружаться после открытия приложения

Необходимая структура кода:
- Запись бюджета должна быть моделью (своим типом данных). Модель должна состоять из имени, типа записи, количества денег, поступление или вычет (буленовская переменная) и даты заметки
- Верстка должна быть адаптивной.  За невыполнение этого пункта минус 0.4 балла
- Дата заметки не должна отображаться в таблице
- Запись бюджета должна иметь конструктор
- Проверка на отрицательное число в сумме денег должна быть сделана внутри set
- Должен быть отдельный файл с generic-методами для сериализации и десериализации
- В коде должны быть не только методы-события, но и самописные методы. Методы должны быть либо private либо public по правилам инкапсуляции

За каждый невыполненный пункт - минус 0.2 балла. Ниже 2 оценка быть не может
