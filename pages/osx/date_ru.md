# date

> Установить или показать системную дату.

- Отобразить текущую дату с использованием формата локали по умолчанию:

`date +"%c"`

- Отобразить текущую дату в формате UTC и ISO 8601:

`date -u +"%Y-%m-%dT%H:%M:%SZ"`

- Показывать текущую дату как временную метку Unix (секунды с начала эпохи Unix):

`date +%s`

- Отобразить определенную дату (представленную как временную метку Unix) с использованием формата по умолчанию:

`date -r 1473305798`