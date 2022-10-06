[< к содержанию](./readme.md)

[< Ветвление в Git](./branching.md)
# Основы слияния
Предположим, вы решили, что работа по проблеме **#53** закончена и её можно влить в ветку **master**. Для этого нужно выполнить слияние ветки **iss53** командой `git checkout iss53`, и переключиться на ветку, в которую вы хотите включить изменения, и выполнить команду `git merge`:

```
$ git checkout master
Switched to branch 'master'
$ git merge iss53
Merge made by the 'recursive' strategy.
index.html |    1 +
1 file changed, 1 insertion(+)
```
![](https://git-scm.com/book/en/v2/images/basic-branching-6.png)

Теперь, когда изменения слиты, ветка **iss53** больше не нужна. Вы можете закрыть задачу в системе отслеживания ошибок и удалить ветку:
```
$ git branch -d iss53
```
---
[< Назад](./branching1.md)