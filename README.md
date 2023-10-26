
# first commit:

-Readme.md
-First
    - first.txt
-Second
    - second.txt

### Переместить один файл ###
Переименовываешь директорию First >> first
Вводишь команду git mv -f First/first.txt first/first.txt
###

# second commit:

-Readme.md
-first
    - first.txt
-Second
    - second.txt
    - someOtherFile.txt // добавлен для сл примра


### Переместить все файлы в папке ###
Переименовываешь директорию Second >> second
Вводишь команду git mv Second/* second
###

# third commit:

-Readme.md
-first
    - first.txt
-second
    - second.txt
    - someOtherFile.txt // добавлен для сл примра