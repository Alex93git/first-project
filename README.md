# Шпаргалка markdown

## Выделение текста

Вы можете выделять текст в markdown с помощью символов `_` или `*`. Например:

Пример _курсива_ и **жирного** текста.

## Заголовки

Заголовки можно создавать с помощью символа `#`. Чем больше `#`, тем меньше заголовок. Например:

# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня

## Выделение кода

Чтобы выделить текст как код, поместите его в тройные кавычки `````. 

```
mkdir my_project
cd my_project
git init
```
Это лишь некоторые функции markdown.


# Git

Git — это система контроля версий, которая помогает отслеживать изменения в проекте. Этот инструмент можно использовать как для индивидуальной, так и для командной работы.

# Инициализируем репозиторий

Сделать папку репозиторием можно с помощью команды - `git init`
Чтобы Git начал отслеживать изменения в проекте, папку с файлами этого проекта нужно сделать **Git-репозиторием** (от англ. _repository_ — «хранилище»). Для этого следует переместиться в неё и ввести команду `git init` (от англ. **init**ialize — «инициализировать»).

Например, создайте папку `first-project` и сделайте её Git-репозиторием: перейдите в неё с помощью команды `cd` и выполните `git init`.

```
$ cd ~/dev/first-project # перешли в нужную папку

$ git init # создали репозиторий
```

