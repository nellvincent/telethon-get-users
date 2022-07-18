# telethon-get-users


Клонируем репозиторий
`git clone https://github.com/nellvincent/telethon-get-users`

Переходим в дирикторию
`cd telethon-get-users`

Устанавливаем нужные пакеты
`pip install -r requirements.txt`

```
# Если нужно установить pip
sudo apt-get install python3-pip
```

Нужно конфигурировать скрипт, в `database.ini` указываем хост, порт, логин пароль и название базы данных. Проходим регистрацию [здесь](https://my.telegram.org/). В файле `launcher.py` на строке 14-16 указываем id приложения, api_hash и свой телефон (там в первый раз придет код, вероятно в ЛС от телеграмм, и если 2фа нужно будет ввести свой пароль)

Чтобы запустить скрипт.
`python3 launcher.py`

