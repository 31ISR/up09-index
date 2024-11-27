# Учебная практика 09

## Содержание

1. [Лидерборд](./leaderboard.ods)
1. [Roadmap](#roadmap)
1. [Как выполнять задания](#как-выполнять-задания)
1. [Документация](#документация)
1. [Полезное](#полезное)

## Roadmap

Все, что находится выше `Мы здесь` должно быть у вас для успешного получения зачета

### 1. Git

[Презентация по Git](https://ktkv-presentations.github.io/algos-8/)

[Интерактивный тренажер по Git](https://ohmygit.org/)

### 2. Терминал

[Интерактивный тренажер по Unix терминалу](https://www.terminaltutor.com/) [en]
или
[Бесплатный курс по терминалу](https://ru.hexlet.io/courses/cli-basics) [ru]

### 3. Django Lab 1

[Лабораторная работа №1](https://github.com/31ISR/up09-lab1)

⬆️ Мы здесь

## Как выполнять задания

В каждом репозитории описано как выполнять задание. В случае, если не указано, то работать по следующему принципу:

> [!warning]
> Перед началом работы с git не забудьте заменить ключ `~/.ssh/id_ed25519` на ваш ключ

### Как начать выполнять

1. Создайте fork репозитория в организации [31ISR](https://github.com/31ISR) под названием `up09-lab{N}-{last_name}`
    - `N` - номер лабораторной работы
    - `last_name` - ваша фамилия
2. Склонируйте себе этот форк по протоколу SSH
    - `git clone {SSH_ПУТЬ_ДО_ВАШЕЙ_РЕПЫ}`
3. Переключитель на ветку `dev`
    - `git branch dev` и `git checkout dev`
4. Выполняйте задания в ветке `dev`

### Как работать

1. Если были изменения в репозитории, то нужно стянуть последние изменения `git pull`
2. Выполняйте задания в ветке `dev`
3. Для отправки ветки `dev` на репозиторий GitHub необходимо:
    - Создать коммит `git add .` и `git commit -m "{Что делали}"`
    - Отправить коммит на GitHub `git push -u origin dev`

### Как сдавать

При успешном выполнении задания:

-   Добавляйте pull request из `dev` в `main` в **вашем репозитории**
-   Указывайте меня ([ktkv419](https://github.com/ktkv419)) как reviewer

При успешной сдаче задания pull request будет закрыт и последним сообщением перед закрытием реквеста будут написаны мои комментарии и оценка

## Установка ПО

### Через WinGet

`winget install python.python.3.12 git.git`

### Через бинарные файлы

- [Git](https://git-scm.com/downloads)
- [Python](https://www.python.org/downloads/)

## Документация

-   [Документация Django](https://www.djangoproject.com/) [en]
-   [Документация Django Rest Framework](https://www.django-rest-framework.org/) [en]
-   [Документация Python](https://docs.python.org/) [en]
-   [Документация Python](http://pydocs.ru/) [ru]

## Полезное

-   [Git шпаргалка](https://github.com/cyberspacedk/Git-commands)
-   [Как использовать SSH ключ на GitHub](https://docs.github.com/ru/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
