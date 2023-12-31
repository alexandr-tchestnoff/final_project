В рамках выполнения дипломного проекта вам предстоит протестировать новый интерфейс авторизации в личном кабинете от заказчика Ростелеком Информационные Технологии. Вам предоставили требования к сайту, внимательно ознакомьтесь с ними перед началом работы.

→ Требования по проекту Требования_SSO_для_тестирования_last.pdf

→ Объект тестирования: https://b2c.passport.rt.ru
Заказчик передал вам следующее задание:

Протестировать требования.

Разработать тест-кейсы (не менее 15). Необходимо применить несколько техник тест-дизайна.

Провести автоматизированное тестирование продукта (не менее 15 автотестов). Заказчик ожидает по одному автотесту на каждый написанный тест-кейс. Оформите свой набор автотестов в GitHub.

Оформить описание обнаруженных дефектов. Во время обучения вы работали с разными сервисами и шаблонами, используйте их для оформления тест-кейсов и обнаруженных дефектов.

Ожидаемый результат:

Перечислены инструменты, которые применялись для тестирования.

Почему именно этот инструмент и эту технику.

Что им проверялось.

Что именно в нем сделано.

К выполненному заданию прикреплены:

Набор тест-кейсов.

Набор автотестов на GitHub. Обратите внимание, что в репозитории должен находиться файл README.md, где будет описано, что именно проверяют данные тестовые сценарии и какие команды необходимо выполнить для запуска тестов. Описанные команды должны работать на любом компьютере с установленными Python3 и PyTest.

Описание оформленных дефектов.

Тест-кейсы доступны по ссылке:https://docs.google.com/spreadsheets/d/1wWIpHVmHMKLhi68oAcyNpK3Gudz6HKHDkco0zYmZc08/edit?usp=sharing
Баг-репорты доступны по ссылке:https://docs.google.com/spreadsheets/d/1KCdNfPtvugcwr2iAW2Yj1sR8qAC1KFfXVMpRHrOBz2U/edit?usp=sharing
В папке pages в файле base_page.py находится конструктор webdriver и общие для всех тестируемых страниц методы.

В папке pages в файлах auth_page.py, change_pass_page.py, reg_page.py находятся методы проверок: файл auth_page.py содержит методы проверок формы авторизации; файл change_pass_page.py содержит методы проверок формы восстановления пароля; файл reg_page.py содержит методы проверок формы регистрации.

В папке tests в файлах test_auth_page.py, test_change_pass_page.py, test_reg_page.py находятся тесты. Все тесты помечены номером, совпадающим с номером тест-кейса в файле: https://docs.google.com/spreadsheets/d/1wWIpHVmHMKLhi68oAcyNpK3Gudz6HKHDkco0zYmZc08/edit?usp=sharing. Во всех файлах с тестами, находятся закомментированные команды для запуска тестов из командной строки (запуск тестов формы авторизации: # python -m pytest -v --tb=line tests/test_auth_page.py; запуск тестов формы восстановления пароля: # python -m pytest -v --tb=line tests/ test_change_pass_page.py; запуск тестов формы регистрации: # python -m pytest -v --tb=line tests/ test_reg_page.py)

В папке pages в файле "locators.py находятся все локаторы.

В корне проекта в файле conftest.py находится фикстура с функцией открытия и закрытия браузера.

В корне проекта в файле settings.py находятся методы и переменные для параметризации тестов

В корне проекта в файле pytest.ini зарегистрированы метки маркировок тестов.

В корне проекта в файле requirements.py описаны используемые библиотеки.
