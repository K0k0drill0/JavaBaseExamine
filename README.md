# JavaBeginTasks
Задания на зачёт

Каждый создаёт свою ветку от main с названием student/номер_группы_фамилия_первая_буква_имени_номер_билета. Делаем пуш только в конце экзамена. Если пуша в конце экзамена нет, то считается, что задача не сдана.

Билет №1:
1.  Класс Object, его методы, правила переопределения методов, использование класса.
2.  Java Memory Model - основные аспекты. Garbage Collector. Garbage Collector G1. СMS.
3.  Реализуйте программу на Java, которая выполняет транформацию отсортированного массива в отсортированный массив квадратов этих чисел за один проход (O(n)). Пример: (-3,-2,-1,0,2) -> (9,4,4,1,0). Приложение должно быть клиент-серверным. Клиент через сокеты отправляет массив на сервер. Сервер выполняет задачу в отдельном потоке и отправляет результат конкретному клиенту.,

Билет №2:
1.  Класс ArrayDeque. Основные реализации. Как работают вставка, удаление, поиск элемента на примере одной из реализаций.
2.  Исключения. Обработка исключений. Проверяемые и непроверяемые исключения. Ключевые слова при использовании исключений.
3.  Реализуйте программу на Java, которая создаёт три потока, которые общаются через одну потокобезопасную коллекцию. В качестве данных используется класс, который содержит обязательное поле типа String, остальные поля на усмотрение разработчика. Первый поток читает данные из указанного файла по строчно в класс (одна строка - один класс), выполняет reverse строки в классе и пишет обратно в коллекцию. Второй поток читает данные, выполняет перевод в верхний регистр только для данных от первого потока и отправляет обратно в коллекцию. Третий поток читает данные, выполняет запись строки в отдельный файл только для данных от второго потока.,

Билет №3:
1.  Многопоточность. Пуллы потоков. ExecutorService. Executors.
2.  Классы, интерфейсы и перечисления. Ключевые слова abstract, interface, enum, default. Разница между абстрактным классом и интерфейсом. Вложенные классы.
3.  Реализуйте программу на Java, которая выполняет транформацию отсортированного массива в отсортированный массив квадратов этих чисел за один проход (O(n)). Пример: (-3,-2,-1,0,2) -> (9,4,4,1,0). Приложение должно быть клиент-серверным. Клиент через сокеты отправляет массив на сервер. Сервер выполняет задачу в отдельном потоке и отправляет результат конкретному клиенту.,

Билет №4:
1.  Stream API. Лямбда-выражения. Основные методы создания, трансформации и агрегации данных.
2.  Типы данных. Преобразования типов. Операции box, unbox. Совместимость типов. Internal Buffer.
3.  Реализуйте программу на Java, которая создает два потока. Первый поток в случайный момент времени пишет свое имя и текущее время в коллекцию очередь (ArrayDeque), а второй поток в случайный момент времени читает строки из очереди и пишет эти строки в файл. Примечание: Нельзя использовать коллекции для многопоточности, пользуйтесь стандартными механизмами синхронизации потоков.,

Билет №5:
1.  Сетевое взаимодействие клиент-сервер в Java. Основные классы и методы для работы с сетью.
2.  Интерфейс Map<K,V>. Основные реализации. Как работают вставка, удаление, поиск элемента на примере одной из реализаций.
3.  Реализуйте программу на Java, которая читает два файла в двух разных потоках. Потоки считывают свои файлы и пишут построчно в потокобезопасную очередь. Третий поток считывает данные из очереди, и записывает в отдельный файл.,

Билет №6:
1.  Библиотека java.util.concurrent.*. Коллекции для работы с многопоточностью.
2.  Параметризация типов. Ковариантность. Контрвариатность. Инвариатность. Использование WildCard.
3.  Реализуйте программу на Java, клиент-серверное (сокеты) приложение. Клиент отправляет на сервер имя файла и ключевое слово. Сервер получает имя файла и ключевое слово. Сервер читает файл, если он есть и отправляет клиенту все строки, в которых есть ключевое слово. Если файла нет или ключевого слова нет, то сервер возвращает ответ, что файла или ключевого слова нет. Сервер постоянно ждёт новых запросов от клиента, клиент постоянно ожидает ввода данных с консоли. Сервер и клиент завершают свою работу только если клиент отправит на сервер команду exit.,

Билет №7:
1.  Многопоточность. Ключевые слова volatile, synchronized. Методы notify, notifyAll, wait.
2.  Неконтроллируемые ресурсы в Java. Интерфейс Autocloseable. try-with-resources. Метод finalize.
3.  Реализуйте программу на Java, которая запускает отдельный поток на чтение файла, раз в заданное время проверяет изменения в файле и записывает в отдельный файл лог изменений этого файла с датой последнего чтения.,

Билет №8:
1.  Класс ArrayList, LinkedList. Основные реализации. Как работают вставка, удаление, поиск элемента на примере реализаций.
2.  Условные операторы(if/else,switch). Операторы циклов (while,do/while,for,foreach,StreamAPI forEach). Интерфейсы Comparable, Comparator. Iterable, Iterator.
3.  Реализуйте программу на Java, выполняющая частотный анализ текста из файла. Необходимо вывести 10 наиболее часто встречающихся триплетов (3 подряд идущих буквы слова, независимо от регистра) и время работы программы в миллисекундах. Обработка файла должна производиться многопоточно.,

Билет №9:
1.  Многопоточность. Интерфейсы Callable, Runnable, Future. Класс Thread.
2.  Интерфейс Set<E>. Основные реализации. Как работают вставка, удаление, поиск элемента на примере одной из реализаций.
3.  Реализуйте программу на Java, которая читает файл построчно и на каждые считанные 10 строк файла запускает другой поток на анализ самой часто встречаемой буквы. После выполнения всех потоков нужно аккумулировать результаты и выдать самую встречающуюся букву.,

Билет №10:
1.  Файлы в Java. Основные потоки чтения/записи. Основные методы работы с потоками чтения/записи.
2.  Наследование, инкапсуляция, полиморфизм. Примеры использования. Ключевое слово final в наследовании. Аннотация @override.
3.  Реализуйте программу на Java, которая считает медиану чисел. Реализовать клиент и сервер (сокеты). Клиент отправляет набор чисел, сервер принимает запрос от клиента, высчитывает медиану и отправляет обратно запросившему клиенту и дальше ждет новых запросов от клиента.,

Билет №11:
1.  Основные методы для работы с коллекциями. Классы Collections, Arrays.
2.  Коллекции Java. Иерархия классов и интерфейсов для коллекций. Примеры.
3.  Реализуйте программу на Java, которая создает два потока. Первый поток в случайный момент времени пишет свое имя и текущее время в коллекцию очередь (ArrayDeque), а второй поток в случайный момент времени читает строки из очереди и пишет эти строки в файл. Примечание: Нельзя использовать коллекции для многопоточности, пользуйтесь стандартными механизмами синхронизации потоков.,

Билет №12:
1.  Типы данных. Преобразования типов. Операции box, unbox. Совместимость типов. Internal Buffer.
2.  Класс ArrayDeque. Основные реализации. Как работают вставка, удаление, поиск элемента на примере одной из реализаций.
3.  Реализуйте программу на Java, клиент-серверное (сокеты) приложение. Клиент отправляет на сервер имя файла и ключевое слово. Сервер получает имя файла и ключевое слово. Сервер читает файл, если он есть и отправляет клиенту все строки, в которых есть ключевое слово. Если файла нет или ключевого слова нет, то сервер возвращает ответ, что файла или ключевого слова нет. Сервер постоянно ждёт новых запросов от клиента, клиент постоянно ожидает ввода данных с консоли. Сервер и клиент завершают свою работу только если клиент отправит на сервер команду exit.,

Билет №13:
1.  Классы, интерфейсы и перечисления. Ключевые слова abstract, interface, enum, default. Разница между абстрактным классом и интерфейсом. Вложенные классы.
2.  Интерфейс Map<K,V>. Основные реализации. Как работают вставка, удаление, поиск элемента на примере одной из реализаций.
3.  Реализуйте программу на Java, которая читает файл, затем создаёт ровно два потока и каждому из потоков отправляет прочитанный текст. Один поток считает сколько раз в тексте встречается каждая буква, другой, каждое слово, где слово - это текст разделённый пробелами.,

Билет №14:
1.  Наследование, инкапсуляция, полиморфизм. Примеры использования. Ключевое слово final в наследовании. Аннотация @override.
2.  Многопоточность. Ключевые слова volatile, synchronized. Методы notify, notifyAll, wait.
3.  Реализуйте программу на Java, которая читает файл, затем создаёт ровно два потока и каждому из потоков отправляет прочитанный текст. Один поток считает сколько раз в тексте встречается каждая буква, другой, каждое слово, где слово - это текст разделённый пробелами.,

Билет №15:
1.  Класс ArrayList, LinkedList. Основные реализации. Как работают вставка, удаление, поиск элемента на примере реализаций.
2.  Коллекции Java. Иерархия классов и интерфейсов для коллекций. Примеры.
3.  Реализуйте программу на Java, которая читает файл построчно и на каждые считанные 10 строк файла запускает другой поток на анализ самой часто встречаемой буквы. После выполнения всех потоков нужно аккумулировать результаты и выдать самую встречающуюся букву.,

Билет №16:
1.  Интерфейс Set<E>. Основные реализации. Как работают вставка, удаление, поиск элемента на примере одной из реализаций.
2.  Библиотека java.util.concurrent.*. Коллекции для работы с многопоточностью.
3.  Реализуйте программу на Java, которая создаёт три потока, которые общаются через одну потокобезопасную коллекцию. В качестве данных используется класс, который содержит обязательное поле типа String, остальные поля на усмотрение разработчика. Первый поток читает данные из указанного файла по строчно в класс (одна строка - один класс), выполняет reverse строки в классе и пишет обратно в коллекцию. Второй поток читает данные, выполняет перевод в верхний регистр только для данных от первого потока и отправляет обратно в коллекцию. Третий поток читает данные, выполняет запись строки в отдельный файл только для данных от второго потока.,

Билет №17:
1.  Неконтроллируемые ресурсы в Java. Интерфейс Autocloseable. try-with-resources. Метод finalize.
2.  Исключения. Обработка исключений. Проверяемые и непроверяемые исключения. Ключевые слова при использовании исключений.
3.  Реализуйте программу на Java, которая считает медиану чисел. Реализовать клиент и сервер (сокеты). Клиент отправляет набор чисел, сервер принимает запрос от клиента, высчитывает медиану и отправляет обратно запросившему клиенту и дальше ждет новых запросов от клиента.,

Билет №18:
1.  Класс Object, его методы, правила переопределения методов, использование класса.
2.  Сетевое взаимодействие клиент-сервер в Java. Основные классы и методы для работы с сетью.
3.  Реализуйте программу на Java, выполняющая частотный анализ текста из файла. Необходимо вывести 10 наиболее часто встречающихся триплетов (3 подряд идущих буквы слова, независимо от регистра) и время работы программы в миллисекундах. Обработка файла должна производиться многопоточно.,

Билет №19:
1.  Многопоточность. Интерфейсы Callable, Runnable, Future. Класс Thread.
2.  Параметризация типов. Ковариантность. Контрвариатность. Инвариатность. Использование WildCard.
3.  Реализуйте программу на Java, в которой необходимо сформировать коллекцию с помощью Stream API на основе входных данных. На вход подается строка с любым набором символов. Необходимо с помощью Stream API получить из этой строки коллекцию с типом String, элементами которой являются сумма всех четных чисел из этой строки(в виде строки), конкатенация всех символов нижнего регистра, и отдельно стоящие символы не буквы и не цифры. Пример: На вход подается строка "aV_1,,.-fg.D42!r" на выходе коллекция ["6","afgr","_", ",",",",".","-",".","!"].,

Билет №20:
1.  Файлы в Java. Основные потоки чтения/записи. Основные методы работы с потоками чтения/записи.
2.  Java Memory Model - основные аспекты. Garbage Collector. Garbage Collector G1. СMS.
3.  Реализуйте программу на Java, которая читает два файла в двух разных потоках. Потоки считывают свои файлы и пишут построчно в потокобезопасную очередь. Третий поток считывает данные из очереди, и записывает в отдельный файл.,

Билет №21:
1.  Stream API. Лямбда-выражения. Основные методы создания, трансформации и агрегации данных.
2.  Основные методы для работы с коллекциями. Классы Collections, Arrays.
3.  Реализуйте программу на Java, которая запускает отдельный поток на чтение файла, раз в заданное время проверяет изменения в файле и записывает в отдельный файл лог изменений этого файла с датой последнего чтения.,

Билет №22:
1.  Условные операторы(if/else,switch). Операторы циклов (while,do/while,for,foreach,StreamAPI forEach). Интерфейсы Comparable, Comparator. Iterable, Iterator.
2.  Многопоточность. Пуллы потоков. ExecutorService. Executors.
3.  Реализуйте программу на Java, в которой необходимо сформировать коллекцию с помощью Stream API на основе входных данных. На вход подается строка с любым набором символов. Необходимо с помощью Stream API получить из этой строки коллекцию с типом String, элементами которой являются сумма всех четных чисел из этой строки(в виде строки), конкатенация всех символов нижнего регистра, и отдельно стоящие символы не буквы и не цифры. Пример: На вход подается строка "aV_1,,.-fg.D42!r" на выходе коллекция ["6","afgr","_", ",",",",".","-",".","!"].,

