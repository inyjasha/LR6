# LR6
Лабораторная работа №6
<<<<<<< HEAD
=======
____

Цель работы: изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и
удаленным репозиторием. 

Для выполнения лабораторной работы был создан аккаунт на github.com. (рис.1.), создана копия в личное хранилище из https://github.com/Kurtyanik/LR6/ (Fork).  Затем был скачан Git и настроен клинет git при помоци команды git config имя пользователя (рис.2) и имейл пользователя (рис.3).
![Alt-Рисунок 1](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/1.jpg "1")

 Рисунок 1. Создание аккаунта на github.com.

![Alt-Рисунок 2.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/2.jpg "2")

 Рисунок 2. Настройка имени пользователя.
 
 ![Alt-Рисунок 3.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/3.jpg "3")
 
  Рисунок 3. Настройка почты пользователя.

Клонируем свой личный удалённый репозиторий на компьютер при помощи команды git clone (рис.4.).
![Alt-Рисунок 4.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/4.jpg "4")

Рисунок 4. Копирование репозитория.

Добавляем файл через интерфейс GitHub. Подтягиваем изменения в локальный репозиторий при помощи команды git pull(рисю 5.). 
![Alt-Рисунок 5.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/5.jpg "5")

Рисунок 5. Подтягивание изменений.

Просмотрим историю операций веток с помощью команды git log (рис 6., 7.) и различные типы объектов (рис. 8., 9.). 
![Alt-Рисунок 6.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/6.jpg "6")

Рисунок 6. История операции ветки master.

![Alt-Рисунок 7.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/7.jpg "7")

Рисунок 7. История операции ветки branch1.

![Alt-Рисунок 8.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/8.jpg "8")

Рисунок 8. Объекты ветки master.

![Alt-Рисунок 9.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/9.jpg "9")

Рисунок 9. Объекты ветки branch1.

Выполнение слияния в ветку master при помощи команды git merge, при ее применении и происходит конфликт в файле (рис. 10.), который отображается в результате применения комонды git status(рис. 11.). Для разрешения конфликта необходимо удалить в файле часть данных и применить команды git add и git commit, git merge (рис. 12). После этого в результате применения команды git status будет выводиться безконфликтное состояние (рис. 13.). 

![Alt-Рисунок 10.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/10.jpg "10")

Рисунок 10. Конфликт.

![Alt-Рисунок 11.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/11.jpg "11")

Рисунок 11. Отображение конфликта.

![Alt-Рисунок 12.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/13.jpg "12")

Рисунок 12. Применение команд git add и git commit, git merge.

![Alt-Рисунок 13.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/12.jpg "13")

Рисунок 13. Безконфликтное состояние.

Удаляем ветку branch1 (рис 14.).

![Alt-Рисунок 14.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/14.jpg "14")

Рисунок 14. Удаление ветки branch1. 

Внесение изменений и их фиксация происходит при изменений файлов вручную и использовании команд git add и git commit (рис. 15., 16., 17., 18.). 

![Alt-Рисунок 15.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/15.jpg "15")

Рисунок 15. Обнаружение изменений в файле. 

![Alt-Рисунок 16.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/16.jpg "16")

Рисунок 16. Первый commit. 

![Alt-Рисунок 17.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/17.jpg "17")

Рисунок 17. Откат первого commit. 

![Alt-Рисунок 18.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/18.jpg "18")

Рисунок 18. Второй commit и откат второго commit. 

Создадим ветку для отчета (рис. 19.).

![Alt-Рисунок 19.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/19.jpg "19")

Рисунок 19. Создание ветки для отчета. 

Файлы для отчета размещаем в папке "otchet", она хранится в папке "LR6", добавим папку со скриншотами (рис. 20.).

![Alt-Рисунок 20.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/20.jpg "20")

Рисунок 20. Добавление папки со скриншотами. 

Получим историю операций в форматированном виде (сокращённый хэш + дата + имя автора + комментарий) при помощи команды git log (рис.21).

![Alt-Рисунок 21.](https://github.com/inyjasha/LR6/blob/branchotchet/otchet/21.jpg "21")

Рисунок 21. Добавление папки со скриншотами. 

Вывод: в ходе лабораторной раоты были получены навыки работы с системой управления версиями, опыт работы с Git Api, опыт работы с локальным и
удаленным репозиторием. 
