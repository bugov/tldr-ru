# prctl

> Получить или установить контроль ресурсов для запущенных процессов,
> задач или проектов.

- Получить лимиты процесса и ограничения:

`prctl {{PID}}`

- Получить лимиты процесса и ограничения в удобном для парсинга формате:

`prctl -P {{PID}}`

- Получить специфичные ограничения для запущенного процесса:

`prctl -n process.max-file-descriptor {{PID}}`