# Подзказка по GIT
* Инициировать файл. Начинает следить за изменениями в данном файле.

```sh
git init

```

* Эта команда показывает изменении и предупреждает если они не сохранены.
```sh
git status
```

* Добавляет и сохраняет изменений.
 ```ah
 git add
 ```

* Позволяет добавить комментарий.
 ```sh
 git commit -m "Message_text"
 ```

* Это коианда позволяет видеть историю коммитов, изменении и кто внёс изминение.
 ```sh
 git log
 ```

* Используется для вывода каждого коммита в одной строке.
 ```sh
 git log --oneline
 ```

* Позволяет переключиться между версиями и вернуться на каждую. 
```sh
git checkout <Имя_ветки>
```

* Отображение всех веток
```sh
git branch
```
* Создание новой ветки
```sh
git branch <имя_ветки>
```

* Используется для удаление ветки
```sh
git branch -d <имя_ветки>

```

* Используется для вывода каждого коммита по схему
```sh
git log --oneline --graph

```

* Это команда помогает объединить ветки
```sh
git merge
```