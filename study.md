# Инструкция по работе с гитом
Чтобы создать репозиторий нужно:

    > git init

Чтобы отслеживать файл с именем file_name, нужно:

    > git add file_name

Для фиксации отслеживаемых файлов нужно:

    > git commit -m "some text"

Отобразить все совершённые коммиты:

    > git log

Чтобы вернуться к предыдущему коммиту с именем commit_code,
используется: 

    > git checkout commit_code

Чтобы вернуться к предыдущему состоянию: 

    > git checkout master

Для просмотра разницы между предыдущим и текущим коммитами:

    > git diff

Чтобы посмотреть все ветки в текущем репозитории:

    > git branch 

Для совмещения веток: 

    > git merge branch_name

Для перехода к ветке с именем branch_name:

    > git checkout branch_name

Чтобы создать и сразу перейти к ветке:

    > git checkout -b branch_name
    
Для создания ветки с именем branch_name:

    > git branch branch_name

Чтобы удалить ветку:

    > git branch -d branch_name

Если нужно изменить без проверки:

    > git branch -D branch name
Можно посмотреть состояние слияний веток добавив к команде git log тэг  --graph

    > git log --graph

Чтобы использовать удалённый репозиторий:

    > git clone <url>

Чтобы получить изменения и слить с локальной версией:

    > git pull

Отправить локальную версию репозитория на внешний:

    > git pull

![a cute racoon!!!](racoon.jpg)