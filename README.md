# КОММАНДЫ ГИТ

**$ pwd** (от англ. _**p**rint **w**orking **d**irectory_ — «показать рабочую папку»). Она выводит путь к текущей директории;


**$ cd** (от англ. _**c**hange **d**irectory_ — «сменить директорию») и символ ~ — обозначение домашней директории. (cd ~).  
cd .. - перейти на уровень вышеcd.  
cd . - перейти в текущую директорию (нужно очень редко для запуска скриптов с папкой как параметром).  
cd c:/ # переместит в корневую директорию.  
Если указать директории через /, то можно перемещаться сразу через несколько директорий;


**$ ls** (от англ. _**l**i**s**t directory contents_ — «отобразить содержимое директории»).  
Флаг (ключ) -a позволяет вывести дополнительные скрытые файлы.
Также работает с ~ и .. ;


**$ touch** "ИМЯ ФАЙЛА" - создать файл.


**$ mkdir** (от англ. _**m**a**k**e **dir**ectory_ — «создать директорию»).  
Можно создать целую структуру директорий одной командой с помощью флага -p, через /.  
*$ mkdir -p dir1/dir-inside/dir-deeper-inside;*


**$ touch** и mkdir можно использовать с ~ ..  
touch ../../file.txt создаст файл на две папки выше;  
Можно создавать файлы в определенной директории, указанной через /  
*$ touch first-project/data.txt first-project/table.csv*


**$ cp** что_копируем куда_копируем. - копирует файл, Можно указать несколько файлов через пробел;


**$ mv** (от англ. _**m**o**v**e_ — «переместить»). То же самое что ctrl+x (вырезать);


**$ cat** (от англ. c_on**cat**enate and print_ — «объединить и распечатать»). Чтобы прочитать файл, в консоль нужно ввести вместе с именем файла.


**$ rm** (от англ. _**r**e**m**ove —_ «удалить») - удалить файл;  
Флаг -r (от англ. _**r**ecursive_, «рекурсивный») позволяет удалить папку вместе с содержимым;


**$ rmdir** -удалить **пустую** директорию. Для удаления НЕПУСТОЙ папки, нужна команда rm -r;


&& позволяет выполнять несколько команд последовательно.  
*$ mkdir second-project && cd second-project && touch index.html style.css*