# **Инструкция по работе с Git**

## What is Git

~~Here we should type what is Git~~

## Creation of the local repositorium

For creating (initializing) the local repositorium it's necessery to type in terminal the command:

    git init

## Проверка состояния репозитория

Чтобы проверить состояние репозтория используют команду

    git status

## Добавление файла для отслеживания

Чтобы включить файл в список отслеживаемых используют команду

    git add
После команды указывают название добавляемого файла

## Фиксация последнего изменения файла

Чтобы зафиксировать текущий статус используют команду

    git commit

Если после этого нажать ENTER, мы попадём в режим, в котором программа предложит нам ввести название этого сохранения. Для этого необходимо нажать i, ввести название, нажать ESC:qw

*Подкоманды*

* Чтобы ввести описании сохраняемой версии сразу в терминале используют команду

  git commid -m

Название вводится после пробела в " "

git commid -a

git commit -am

git log

git log oneline

git checkout
  позволяет выбрать сохранение, набрав его название

git checkout master
  позволяет вернутся на текущее сохранение
git diff
  kvierhligerhggit