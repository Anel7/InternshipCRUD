Тестовое задание на стажировку JavaRush

[Скрипт для создания таблицы в БД и наполнения ее данными](https://github.com/Anel7/InternshipCRUD/blob/master/src/main/resources/DBCreation.sql)<br>
расположен по адресу **/src/main/resources/DBCreation.sql**

Подключение к БД: **database: test | username: root | password: root**

Реализованная функциональность (помимо удаления/создания/редактирования записей):<br>
1. Бизнес требование 1 реализовано через кнопку в стобце "Прочитано / Не прочитано" списка всех книг
2. Добавлена возможность фильтрации по полям "Id", "Наименование", "Автор", "Год печати", "Статус прочтения". Поддерживается одновременная фильтрация по нескольким полям. 
  * Фильтрация по полям "Id", "Год печати" производится по точному соответствию; 
  * Фильтрация по полям "Наименование", "Автор" производится по маске. 
  * Фитрация по полю "Статус прочтения" - выбор из соответствующего списка.
3. Добавлена проверка Spring Validation для полей формы добавления/редактирования книги.
4. Реализована возможность выбора числа отображаемых строк на экране списка всех книг.

![Preview](https://github.com/Anel7/InternshipCRUD/blob/master/readme_img/MainScreen.jpg)
