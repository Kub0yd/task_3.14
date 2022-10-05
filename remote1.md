[< к содержанию](./readme.md)

# Просмотр удалённых репозиториев

Для того, чтобы просмотреть список настроенных удалённых репозиториев, вы можете запустить команду `git remote`. Она выведет названия доступных удалённых репозиториев. Если вы клонировали репозиторий, то увидите как минимум **origin** — имя по умолчанию, которое Git даёт серверу, с которого производилось клонирование:
```
$ git clone https://github.com/Kub0yd/task_3.14
Cloning into 'task_3.14'...
remote: Reusing existing pack: 1857, done.
remote: Total 1857 (delta 0), reused 0 (delta 0)
Receiving objects: 100% (1857/1857), 374.35 KiB | 268.00 KiB/s, done.
Resolving deltas: 100% (772/772), done.
Checking connectivity... done.
$ cd task_3.14
$ git remote
origin
```

Вы можете также указать ключ -v, чтобы просмотреть адреса для чтения и записи, привязанные к репозиторию:
```
$ git remote -v
origin  https://github.com/Kub0yd/task_3.14 (fetch)
origin  https://github.com/Kub0yd/task_3.14 (push)
```