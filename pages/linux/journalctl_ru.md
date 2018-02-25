# journalctl

> Средство обращения к журналу systemd.

- Вывести сообщения, относящиеся к текущему запуску системы:

`journalctl -b`

- Вывести сообщения, относящиеся к предыдущему запуску системы:

`journalctl -b -1`

- Отслеживать появление новых сообщений (аналог `tail -f`):

`journalctl -f`

- Вывести сообщения относящиеся к заданному юниту:

`journalctl -u {{unit}}`

- Вывести сообщения, относящиеся к заданному процессу:

`journalctl _PID={{pid}}`

- Вывести сообщения относящиеся к заданному исполняемому файлу:

`journalctl {{/path/to/executable}}`