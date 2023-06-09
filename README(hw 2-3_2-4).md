# Учебный проект **IT switcher**

## Работа с *Git*

### _Команды *git pull* и *git fetch* в чем отличие?_

- *git pull* - извлекает данные с удаленного репозитория на локальный и вносит все изменения (commits) сделанные на удаленном репозитории в локальный репозиторий (сливает код).
- *git fetch* - только **извлекает данные** из удаленного репозитория и переносит на локальный **изменения не вносит**.
- *git merge* - еще одна команда  раскрывающая отличие *git pull* от *git fetch*, она сливает уже скачанный с удаленного репозитория код и вносит изменения в рабочую ветку.

#### Таким образом, *git pull* = (*git fetch*+*git merge*)

[описание](https://webhamster.ru/mytetrashare/index/mtb0/143575842521lohpnj4q)

### Команда *git commit --amend*

Команда *git commit --amend* позволяет добавить новые проиндексированные изменения в последний коммит. С помощью коммита *--amend* можно добавлять изменения в индекс *Git* или удалять таковые из него. Если никаких изменений не проиндексировано, при использовании флага *--amend* вам все равно будет предложено изменить комментарий к последнему коммиту. Будьте осторожны при использовании флага *--amend* с коммитами, доступными другим членам команды. Изменение коммита, доступного другому пользователю, может привести к путанице и длительным устранениям конфликтов при слиянии.
