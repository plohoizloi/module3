***[< к содержанию](/README.md)***

# **Подготовка к работе с GIT**

1. **Установка имени и электронной почты**

Если вы никогда ранее не использовали Git, для начала вам необходимо осуществить установку. Выполните следующие команды, чтобы Git узнал ваше имя и электронную почту. Эти данные используются для подписи изменений сделанных вами, что позволит отслеживать, кто и когда сделал изменения в файле.

    git config --global user.name "Your Name"
    git config --global user.email "your_email@whatever.com"

2. **Имя ветки по умолчанию**

Мы будем использовать main в качестве имени ветки по умолчанию. Чтобы установить его, выполните следующую команду:

    git config --global init.defaultBranch main

3. **Корректная обработка окончаний строк**

Для пользователей Unix/Mac:

    git config --global core.autocrlf input
    git config --global core.safecrlf warn

Для пользователей Windows:

    git config --global core.autocrlf true
    git config --global core.safecrlf warn


