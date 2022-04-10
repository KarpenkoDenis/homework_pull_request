![git logo](git_logo.webp)

# Инструкция по работе с Git 

1. Скачать Git можно по [ссылке](https://git-scm.com/downloads)

2. Для создания локального репозитория нужно запустить команду (см. [инструкцию](https://git-scm.com/docs/git-init)):
```sh
git init
```

3. Для добавления файла к следующему коммиту (см. [инструкцию](https://git-scm.com/docs/git-add)):
```sh
git add
```

и фиксируем эти файлы (см. [инструкцию](https://git-scm.com/docs/git-commit)):
```sh
git commit -m "<message>"
```

4. Можно обьеденить команду add и commit:
```sh
git commit -a -m "<message>"
```

5. Для отслеживания состояния репозитория, можно использовать следующую команду (см. [инструкцию](https://git-scm.com/docs/git-status)):
```sh
git status
```

6. Чтобы посмотреть все коммиты (см. [инструкцию](https://git-scm.com/docs/git-log)):
```sh
git log
```

7. Для просмотра разницы между закоммиченными и текущими изменениями (см. [инструкцию](https://git-scm.com/docs/git-diff)):
```sh
git diff
```

8. Для перехода к прошлым коммитам (с кодом ***`commit_code`***) можно использовать (см. [инструкцию](https://git-scm.com/docs/git-checkout)):
```sh
git checkout <commit_code>
```

и чтобы вернуться:
```sh
git checkout master
```

9. Для просмотра всех веток (см. [инструкцию](https://git-scm.com/docs/git-branch)):
```sh
git branch
```

10. Чтобы создать ветку, нужно:
```sh
git branch <branch_name>
```

11. Для перехода к ветке <branch_name> (см. [инструкцию](https://git-scm.com/docs/git-checkout)):
```sh
git checkout <branch_name>
```

12. Для совмещения текущей ветки с веткой <branch_name> (см. [инструкцию](https://git-scm.com/docs/git-merge)):
```sh
git merge <branch_name>
```

13. Для того, чтобы удалить ветку <branch_name> (см. [инструкцию](https://git-scm.com/docs/git-branch)):
```sh
git branch -d <branch_name>
```

 ## Основные команды Git
 ***

| Command | Description |
| ------------------- | ------------------- |
| `git init`  | инициализация локального репозитория |
| `git status` |получить информацию от git о его текущем состоянии |
| `git add` |добавить файл или файлы к следующему коммиту|
| `git commit -m “message”` | создание коммита |
| `git log` |вывод на экран истории всех коммитов с их хеш-кодами|
| `git checkout <commit_code>`  |переход от одного коммита к другому|
| `git checkout master`|  вернуться к актуальному состоянию и продолжить работу|
| `git diff` | увидеть разницу между текущим файлом и закоммиченным файлом |
| `git branch` | посмотреть ветки |
| `git branch <branch_name>` | создать новую ветку |
| `git checkout <branch_name>` | переход на другую ветку |
| `git merge <branch_name>` | обьеденить текущую ветку с веткой <branch_name> |
| `git branch -d <branch_name>` | удалить ветку |
