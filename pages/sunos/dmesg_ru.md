# dmesg

> Записать сообщение ядра в стандартный поток вывода.

- Показать сообщения ядра:

`dmesg`

- Показать сколько физической памяти доступно в системе:

`dmesg | grep -i memory`

- Показать сообщения ядра, только первую страницу вывода (постраничный вывод):

`dmesg | less`
