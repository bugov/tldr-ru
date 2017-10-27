# mkfs.vfat

> Создает файловую систему VFAT (MS-DOS) на разделе.

- Создать файловую систему VFAT (MS-DOS) на разделе `1` устройства `b` (`sdb1`):

`mkfs.vfat {{/dev/sdb1}}`

- Создать файловую систему VFAT (MS-DOS) и задать метку тома:

`mkfs.vfat -n {{volume_name}} {{/dev/sdb1}}`

- Создать файловую систему VFAT (MS-DOS) и задать идентификатор тома:

`mkfs.vfat -i {{volume_id}} {{/dev/sdb1}}`

- Использовать 5 таблиц размещения файлов (по умолчанию используется 2):

`mkfs.vfat -f 5 {{/dev/sdb1}}`