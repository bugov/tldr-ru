# lldb

> Низкоуровневый отладчик LLVM.

- Запустить отладку исполняемого файла:

`lldb {{executable}}`

- Запустить отладку процесса по его идентификатору:

`lldb -p {{pid}}`

- Запустить отладку процесса при его запуске:

`lldb -w -n {{process_name}}`