
Для того, чтобы проверить статус вашей рабочей директории и области индексации, необходимо написать:
```GIT
git status
```

```ad-success
title: Результат работы команды, если файлов нет
Если нет никаких новых файлов, то выведется надпись **Nothing to commit, working tree clean**
```

```ad-success
title: Результат работы команды, если есть новые файлы
Если вы добавили новые файлы, то они отобразятся в блоке **Untracked files**
```

```ad-success
title: Результат работы команды, если есть файлы в области Индексации
Если вы добавили файлы в область Индексации, то они отобразятся в блоке **Changes to be committed**
```

```ad-success
title: Результат работы команды, если изменились файлы в области Репозитория
Если файлы в области репозитория изменены, то они отобразятся в блоке **Changes not staged for commit**
```

[[Git_statuses|Подробнее о статусах файлов в Git]]