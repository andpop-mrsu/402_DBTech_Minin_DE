# Описание проекта
Игра "Виселица" (hangman). Компьютер загадывает слово из шести букв и рисует на странице отдельные пустые клетки для каждой буквы. Игрок пытается угадать буквы, а затем и все слово целиком. Если игрок правильно угадывает букву, компьютер вписывает ее в клетку. Если ошибается, то рисует одну из частей тела повешенного человека. Чтобы победить, игрок должен угадать все буквы в слове до того, как повешенный человечек будет полностью нарисован.

### Требования
* Браузер, поддерживающий ECMAScript 6
* Минимальная версия PHP: 7.4.10
* Минимальная версия SQLite3: 3.31.1

### Инструкция по запуску игры:
Загрузить проект на локальную машину; 
установить composer, если он не установлен; 
перейти в корневой каталог; 
выполнить в консоли команды composer update и php -S localhost:3000 -t public; 
перейти в браузере на страницу http://localhost:3000/index.html или http://localhost:3000;
следовать указаниям игры.