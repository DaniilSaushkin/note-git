
В Git есть три области:
- **Working directory** (Рабочая директория) - это ваш проект, где вы работаете и храните свои файлы.
- **Staging area** (Индекс) - это область, где вы фиксируете изменения, которые хотите сохранить в репозиторий.
- **Repository** (Репозиторий) - это область с сохранёнными снимками вашей рабочей директории. То есть, это то место, где Git хранит все данные.

Для того, чтобы перенести файлы из **working directory** в **staging area** нужно прописать команду:
```GIT
git add "перечислить файлы для добавления"
```
Либо, чтобы добавить все файлы можно написать:
```GIT
git add .
```

А затем уже, чтобы перенести файлы из **staging area** в **repository** нужно прописать:
```GIT
git commit
```
