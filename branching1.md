[< к содержанию](./readme.md)


# Основы ветвления
Предположим, вы работаете над проектом и уже имеете несколько коммитов.
![](https://git-scm.com/book/en/v2/images/basic-branching-2.png)

Вы решаете, что теперь вы будете заниматься проблемой **#53** из вашей системы отслеживания ошибок. Чтобы создать ветку и сразу переключиться на нее, можно выполнить команду `git checkout` с параметром **-b**:
```
$ git checkout -b iss53
Switched to a new branch "iss53"
```
После добавления коммитов ветка движется вперед
![](https://git-scm.com/book/en/v2/images/basic-branching-3.png)

---
[< Назад](./branching.md)

[Далее >](./branching2.md)