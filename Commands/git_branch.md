
Для того, чтобы изменить название ТЕКУЩЕЙ ветки, нужно написать:
```GIT
git branch -m "название ветки"
```

Для создания новой ветки нужно прописать команду:
```GIT
git branch "название ветки"
```
или можно сделать следующим образом, создать новую ветку и переключиться на неё командой:
```GIT
git checkout -b "название ветки"
```

Для переключения на другую ветку нужно написать:
```GIT
git switch "название ветки"
```
или
```GIT
git checkout "название ветки"
```

Для удаления ветки, нужно написать команду:
```GIT
git branch -d "название ветки"
```
перед удалением ветки из неё нужно выйти в другую ветку

Для объединения веток, нужно использовать команду [[git_merge|git merge]].
