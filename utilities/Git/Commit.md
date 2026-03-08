# Коммит изменений 

`git commit` - откроет выбранный вами текстовый редактор. #GitCreateCommit  
 ├── `-m` _Название коммита_ - фиксация изменений. #GitCreateCommitShort  
 ├── `-v` - в комментарий будет также помещена дельта/diff изменений. #GitCreateCommitDetailed  
 └── `--amend` - вносит в коммит файлы которые были добавлены в staged после коммита. #GitCommitAmend  
 
В редакторе будет отображён следующий текст (это пример окна Vim):

```
# Please enter the commit message for your changes. Lines starting
# with '#' will be ignored, and an empty message aborts the commit.
# On branch master
# Your branch is up-to-date with 'origin/master'.
#
# Changes to be committed:
#	new file:   README
#	modified:   CONTRIBUTING.md
#
~
~
~
".git/COMMIT_EDITMSG" 9L, 283C
```

По умолчанию для коммита содержит закомментированный результат работы команды git status и ещё одну пустую строку сверху.  
Вы можете удалить эти комментарии и набрать своё сообщение или же оставить их для напоминания о том, что вы фиксируете.

`git restore` _Файл_ - откатывает файл до состояния последнего коммита. #GitRestoreFile  
 └── `--staged` - отмена индексации файла. #GitRestoreStaged  
