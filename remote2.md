[< к содержанию](./readme.md)

[< Работа с удалёнными репозиториями](./remote.md)

# Добавление удалённых репозиториев


Для того, чтобы добавить удалённый репозиторий и присвоить ему имя *(shortname)*, просто выполните команду `git remote add <shortname> <url>`:

```
$ git remote
origin
$ git remote add pb https://github.com/Kub0yd/task_3.14
$ git remote -v
origin	https://github.com/schacon/task_3.14  (fetch)
origin	https://github.com/schacon/task_3.14 (push)
pb	https://github.com/Kub0yd/task_3.14 (fetch)
pb	https://github.com/Kub0yd/task_3.14 (push)
```

Теперь вместо указания полного пути вы можете использовать pb. Например, если вы хотите получить изменения, которых у вас нет, вы можете выполнить команду `git fetch pb`:
```
$ git fetch pb
remote: Counting objects: 43, done.
remote: Compressing objects: 100% (36/36), done.
remote: Total 43 (delta 10), reused 31 (delta 5)
Unpacking objects: 100% (43/43), done.
From https://github.com/Kub0yd/task_3.14
 * [new branch]      master     -> pb/master
 * [new branch]      ticgit     -> pb/task_3.14
```
---
[< Назад](./remote1.md)

[Далее >](./remote3.md)