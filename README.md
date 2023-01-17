# Rostelecom_Test_UI
The repository was created using the template PageObject, Selenium, PyTest (Python).  The project contains UI tests "Rostelecom": https://b2c.passport.rt.ru


Проект содержит UI тесты сайта "Ростелеком": https://b2c.passport.rt.ru

Примечание:

Если вы используете PyCharm, он автоматически запрашивает установку необходимых библиотек.
Если нет - установите требуемые библиотеки в файле requirements.txt.


Файлы:

в папке tests: 

               test_rostelecom.py - автотесты

               driver.exe - Chromedriver

в папке Pages: 

               base.py -  библиотека Smart Page Object

               auth_page.py - класс для страницы "Авторизация"

               auth_page_with_code.py - класс для страницы "Авторизация с временным кодом"

               elements.py - класс для определения элементов на веб-страницах

               register_page.py - класс для страницы "Регистрация"

Запуск тестов:
 
python -m pytest -v --driver Chrome --driver-path driver.exe
