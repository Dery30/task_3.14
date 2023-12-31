[*<К содержанию*](/readme.md)
## Ветвление и слияние GIT


* Команда ***git branch*** — это своего рода *“менеджер веток”*. Она умеет перечислять ваши ветки, создавать новые, удалять и переименовывать их.
```
git branch
```
* Команда ***git checkout*** используется для переключения веток и выгрузки их содержимого в рабочую директорию.
```
git checkout
```
* Команда ***git merge*** используется для слияния одной или нескольких веток в текущую. Затем она устанавливает указатель текущей ветки на результирующий коммит.
```
git merge
```
* Команда ***git mergetool*** просто вызывает внешнюю программу слияний, в случае если у вас возникли проблемы слияния.
```
git mergetool
```
* Команда ***git log*** используется для просмотра истории коммитов, начиная с самого свежего и уходя к истокам проекта. По умолчанию, она показывает лишь историю текущей ветки, но может быть настроена на вывод истории других, даже нескольких сразу, веток. Также её можно использовать для просмотра различий между ветками на уровне коммитов.
```
git log
```
* Команда ***git stash*** используется для временного сохранения всех незакоммиченных изменений для очистки рабочей директории без необходимости коммитить незавершённую работу в новую ветку.
```
git stash
```
* Команда ***git tag***используется для задания постоянной метки на какой-либо момент в истории проекта. Обычно она используется для релизов.
```
git tag
```


