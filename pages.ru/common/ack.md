# ack

> Утилита для поиска, подобная grep, оптимизировання для программистов.
> Больше информации: <https://beyondgrep.com/documentation>.

- Найти файлы, содержащие "foo":

`ack {{foo}}`

- Найти файлы заданного типа:

`ack --ruby {{foo}}`

- Подсчитать общее число совпадений для термина "foo":

`ack -ch {{foo}}`

- Показать имен файлов, содержащие "foo" и число совпадений в каждом файле:

`ack -cl {{foo}}`

- Поиск заданной строки в файле:

`ack bar "{{foo bar}}" {{путь/до/файла}}`

- Поиск в файле по заданному регулярному выражению:

`ack bar "{{[bB]ar \d+}}" {{путь/до/файла}}`

- Вывести список всех допустимых типов:

`ack --help-types`
