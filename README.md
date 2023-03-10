# module-1-12lab
1ый модуль: создание заданий и отслеживание их выполнения.

Данная программа предназначена для создания, просмотра, выполнения и удаления задач, а также для просмотра профиля пользователя.

Входные данные: 
• Названия заданий; 
• Дата и время завершения заданий.

Выходные данные:
• Список заданий;
• Кабинет пользователя.

Процесс работы программы: 
1. Запуск программы. 
2. Отображение меню. 
3. Выбор действия пользователем.
4. В зависимости от Вашего выбора будет выполнено следующее действие: 
• Создание задания: ввод названия задания и даты и времени завершения задания пользователем. Создание объекта структуры Task с указанными пользователем данными.
• Просмотр заданий: вывод списка заданий с маркировкой «выполнено» или «провалено».
• Завершение задания: ввод номера задания пользователем и его пометка выполненным.  
• Удаление задания: ввод номера задания пользователем и его удаление.     
• Профиль: вывод статистики по активным заданиям (сколько выполнено, сколько провалено).
• Выход: Завершение программы.

Дополнительно: 

• Для установки русского языка используется функция setRussianLocale().

• Для получения точки времени из даты и времени используется функция std::chrono::system_clock::from_time_t().

• Для получения даты и времени из точки времени используется функция std::mktime().

• Для ввода даты и времени используется функция std::get_time().

• Для создания структуры Task используется функция createTask(), принимающая на вход название и точку времени дедлайна.

• Для отображения заданий используется функция showTasks(), принимающая на вход вектор структур Task. 

• Для пометки задания как выполненного используется функция markTaskAsCompleted(). 

• Для удаления задания используется функция deleteTask().

• Для показа личного кабинета используется функция showPersonalCabinet(), принимающая на вход вектор структур Task. 

• Для отрисовки меню используется функция drawMenu().

