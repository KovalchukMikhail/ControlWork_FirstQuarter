# Контрольная работа №1

## Общая часть.

Данный репозиторий содержит выполненную контрольную работу за первую четверть обучения.

### Текст задания.
Данная работа необходима для проверки ваших знаний и навыков по итогу прохождения первого блока обучения на программе разработчик. Мы должны убедиться что базовое знакомство с IT прошло успешно.

Задача алгоритмически не самая сложная, однако для полноценного выполнения проверочной работы необходимо:

1. Создать репозиторий на GitHub.

2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете ее в отдельный метод).

3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)

4. Написать программу, решающую поставленную задачу.

5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так что все залито одним коммитом, как минимум 2, 3 и 4 должны быть расположены в разных коммитах)

### Задача:

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

### Примеры:

["hello", "2", "world", ":-)"] -> ["2", ":-)"]

["1234", "1567", "-2", "computer science"] -> ["-2"]

["Russia", "Denmark", "Kazan"] -> []


## Описание выполненной работы

1. Был создан репозиторий на GitHub.

2. Была создана блок-схема. Алгоритм отображенный в блок-схеме можно условно разделить на 4 части.
* Задание исходного массива. Пользователь сам указывает размер массива и вводит по очереди каждый элемент массива.
* Вывод исходного массива в терминале.
* Создание нового массива на основе исходного в соответствии с заданием. Алгоритм создания нового массива из исходного разбит на 2 этапа. На первом этапе создается переменная count в которой подсчитывается количество элементов массива отвечающих условиям задачи. На втором этапе создается массив c длиной равной count и заполняется по очереди элементами из исходного массива отвечающими условию задачи.
* Вывод результирующего массива в терминале.

3. Репозиторий снабжен оформленным текстовым описанием решения (файл README.md)

4. Создана программа решающая поставленную задачу. Программа содержится в файле Programe.cs в котором реализовано решение поставленной задачи. Основное тело программы содержит запрос от пользователя размера исходного массива, вывод комментариев по ходу выполнения программы и обращения к методам в которых реализованы следующие части программы:
* Метод FillArray заполняет исходный массив поэлементно запрашивая значения от пользователя.
* Метод ChangeArray заполняет новый массив в соответствии с условием задачи.
* Метод ShowArray выводит массив в терминал.

5. По ходу реализации задачи для разных этапов были созданы соответствующии коммиты.