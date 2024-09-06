***[< к содержанию](/README.md)***

# **Изменения в ветке main**

Как я уже говорил, Git позволяет работать с несколькими ветками одновременно. Это очень удобно при работе в команде, поскольку люди могут параллельно работать над разными функциями. Это также полезно при работе в одиночку: разрабатывая функции в отдельных ветках, вы можете исправлять ошибки и выпускать небольшие обновления, используя стабильный код в ветке main.

1. **Создайте файл README**

Создадим файл README. В нем будет рассказано о сути нашего проекта.

*Файл: README*

    This is the Hello World example from the GitHowTo tutorial.

2. **Сделайте коммит файла README в ветку main**

В настоящее время мы находимся в ветке ***style***. Файл README не является частью этой ветки, поэтому перед коммитом мы должны переключиться на ветку ***main***.

*Выполните*

    git switch main
    git add README
    git commit -m "Added README"

*Результат*

    $ git switch main
    Switched to branch 'main'
    $ git add README
    $ git commit -m "Added README"
    [main ee16740] Added README
    1 file changed, 1 insertion(+)
    create mode 100644 README