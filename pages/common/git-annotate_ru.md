# git annotate

> Показывает хеш коммита и последнего автора для каждой строки файла.
> Также обратите внимание на `git blame`, использование которого предпочтительнее `git annotate`.
> `git annotate` поставляется для тех, кто привык к данной функциональности в других системах контроля версий.

- Вывести файл с именами авторов и хешами коммитов для каждой строки:

`git annotate {{path/to/file}}`

- Вывести файл с email-ами авторов и хешами коммитов перед каждой строкой:

`git annotate -e {{path/to/file}}`
