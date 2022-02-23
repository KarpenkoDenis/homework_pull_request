>git log

 Просмотр логов в виде графов:
 >git log –graph

 Просмотр ветвей репозитория:
 >git branch

 Перемещение к коммиту:
 >git checkout commit_code

 Просмотр статуса:
 >git status

 Клонирование репозитория на локальный:
 >git clone git_HTTPS folder_name

 Забираем изменения с удалённого репозитория на локальный:
 >git pull 

 Специальное слияние файлов, в котором они будут идти друг за другом:
 >git pull --rebase

 Добавление изменений в локальный репозиторий:
 >git add .

 Добавление коммита:
 >git commit -a -m "Some message"

 >git remote add origin git_HTTPS

 Замена данных на удалённом репозитории в origin master данными на локальном:
 >git push origin master

 Обозначение того, чтобы Push совершался по умолчанию в origin master:
 >git push --set-upstream origin master
 
 Замена данных на удалённом репозитории данными на локальном:
 >git push