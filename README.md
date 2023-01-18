# Добавление сервере в домен AD 
![Powershell](https://www.leixue.com/uploads/2020/04/PowerShell.jpg)
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/serehpst/AddingToDomain)
[![AD](https://img.shields.io/badge/code%20style-goodparts-brightgreen.svg?style=flat)](https://github.com/dwyl/goodparts "AD")
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/serehpst/AddingToDomain/issues)

Данный PоwerShell скрипт добавляет сервер в домен Active Directory
## Как это работает 🤔
Обычно скрипт просит предоставить IP контроллера домена, что является главным требованием при добавлении сервера в домен. После этого он обычно просит указать имя домена, например xyz.com, и перезагружает сервер без предварительного запроса.
## Вероятный результат 👀
После запуска этого скрипта первым делом войдите в систему с доменными учетными данными, чтобы проверить, можете ли вы войти в систему или нет.
## Требования 🐱‍💻
Windows Server 2008 R2 и выше