# Shell на Java

### Задание для Факультета разработки ПО в КРОК

**Пример запуска:** java -jar shell.jar [file_name]

## Команды
* **cd path** - переход в директорию *path*
* **mkdir dir** - создание директори *dir*
* **ls dir** - список всех файлов и директорий в директории *dir*; если директория *dir* не указана, то вывод осуществляется для текущей директории.
* **rm path** - удалить файл или директорию *path*; если *path* - директория, то дополнительно нужно указать флаг *-r*
* **head file_name -n k** - вывести первые *k* строк для файлаа *file_name*
* **mkfile file_name** - создать пустой файл *file_name*
* **echo file_name "text"** - дописать *text* в файл *file_name*; кавычки могут быть либо двойными, либо одинарными
