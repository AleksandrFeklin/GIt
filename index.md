# Инструкция по работе с "GIT"

## **Задать имя пользователя и адрес электронной почты**

*Для ввода имени пользователя и адреса электронной почты используются команды:*

```
git config --global user.name "имя пользователя"

git config --global user.email "адрес электронной почты"
```

## **Создание репозитория**
*Для создания репозитория используется команда:*

```
mkdir <имя репозитория>
```

## **Инициализация репозитория**

*Для инициализации репозитория в текущей директории нужно ввести команду :*
```
git init
```
## **Создание файла**

*Для создания файла в репозитории нужно использовать команду:*
```
touch <имя файла>
```
## **Добавление файлов в коммит**

*Для добавления файлов в коммит используется команда:*

```
git add <имя файла>
```
**или** 
```
git add .
```


## **Добавление коммита**

*Для добавление коммита используется команда:*

```
git commit -m "Название коммита"
```

## **Проверка статуса изменения файлов в "GIT"**

*Для проверки изменения статуса используется команда :*

```
git status
```

## **Просмотр истории коммитов в "Git"**
*Для проверки статуса используется команда:*

```
git log
```

## **Отмена изменений**

*Для отмены действий используется команда :*

```
git checkout <идентификатор коммита>
```

## **Удаление коммитов**

*Для удаления коммитов используется команда:*

```
git reset <идентификатор коммита>

```
## **Клонирование репозитория**

*Для клонирования репозиторя используется команда:*

```
git clone <ссылка на репозиторий>
```
## **Обновление текущей ветки**

*Для обновления  текущей ветки используется команда:*

```
git pull
```
## **Перенос изменений в удалённый репозиторий**

*Для переноса текущей ветки в удалённый репозиторий используется команда:*
```
git push
```

## **Загрузка изменений из всех веток**
*Для  изменений всех веток используется команда:*
```
git fetch
```

## Полезные ссылки: