# testProjectPHP

  Проект реализован на чистом PHP и JS. Для верстки использовался Bootstrap. Проект разделен на классы. 
Постарался разнести логику приложения на логические уровни(MVC), где контроллер представлен в виде анонимных функций,
модель представленна классом Repository, а представление шаблонами.

  Подключение к БД происходит при помощи PDO. PDO позволяет сильно повысить защиту веб сайта от SQL инъекций. Пароли 
до занесения в базу шифруются.

  Приложение работает по Front-Controller где входным файлом является index.php. Реализован базовый роутинг. Авторизация
работает при помощи встроенного механизка сессий.

  Пользователь может прикрепить к форме один файл с расширение jpeg, gif, png. Максимальный размер и тип файла проверяется
до сохранения на сервере и в базе.

  Реализован механизм смены языка с помощью сессии и дополнительных шаблонов. Ошибки динамически выводятся и также меняют язык.
  
  Валидация простая без применения сложной логики и регулярок. Валидация происходит как на сервере так и с JS без применения
сторонних библиотек.

Проект разрабатывал при при помощи OpenServer
Проект работает на http://test


