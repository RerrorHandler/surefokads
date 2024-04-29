## Setup

Чтобы получить этот репозиторий, запустите следующую команду в вашем терминале с поддержкой git

$ git clone https://github.com/RerrorHandler/surefokads.git

Для запуска этого приложения на вашем компьютере должен быть установлен django. Перейдите по ссылке https://www.djangoproject.com/download/, чтобы ознакомиться с руководством по загрузке

После загрузки django перейдите в каталог клонированного репозитория и выполните следующую команду

$ python manage.py makemigrations

Это создаст все файлы миграции (миграции базы данных), необходимые для запуска этого приложения.

Теперь, чтобы применить эту миграцию, выполните следующую команду

$ python manage.py migrate

Последний шаг, и наше приложение surefokads заработает. Нам нужно создать пользователя с правами администратора, чтобы запустить это приложение. В терминале введите следующую команду и укажите имя пользователя, пароль и адрес электронной почты для пользователя с правами администратора

$ python manage.py createsuperuser

Это было довольно просто, не так ли? Теперь давайте запустим приложение. Нам просто нужно запустить сервер прямо сейчас, и тогда мы сможем начать использовать наше простое приложение для выполнения текущих задач. Запустите сервер, выполнив следующую команду

$ python manage.py запустите сервер

Как только сервер будет размещен, перейдите по ссылке http://127.0.0.1:8000/surefokads для поиска приложения.

Приветствую вас и желаю удачного написания кода :)