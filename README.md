# hh-school-search
## Дз по поиску 

Программа написана БЕЗ! использованием Apache Lucene, к сожалению.
Времени мало, потому функционал урезан. Проверка на предлоги короткая (только "in", "at" - для более реалистичного поведения)
Пути файлов не сохраняю. Если это необходимо, то просто создается еще одна табличка (индекс - путь), но у меня все хранится в 1 таблице (терм - имя файла).
Конечно, это самая тривиальная программа, но, как повторюсь, не успеваю сделать продвинутее.

Можно указать путь до индекса, директории индекса или указать путь, по которому автоматически создадутся все подпапки + index.txt

Поиск осуществляется по одному слову.

Запуск проекта:
1. mvn compile package
2. java -jar ./target/homework-1.0-SNAPSHOT-jar-with-dependencies.jar

Главное меню:
----
<p>Индексация             [1]</p>
<p>Поиск по индексу       [2]</p>
<p>Выход из приложения    [3]</p>
<p>Введите номер меню:


Индексация:
----
<p>Введите расположение индекса:</p>
<p>Введите расположение индексируемого файла:</p>


Поиск по индексу:
----
<p>Введите расположение индекса:</p>
<p>Введите запрос:</p>



## Дополнительный функционал: 
Не делал. Из дополнительного была реализация на Lucene (предыдущий коммит)

## Срок выполнения

21.01.2020 04.06 / 30.01.2020 22.27
