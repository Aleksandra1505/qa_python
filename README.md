##Тесты для метода add_new_book
Этот метод отвечает за добавление новых книг к коллекцию.
При проверке работы этого метода проверяю следующие сценарии:
1. Добавление новой книги, когда ее название валидно и уникально
2. Невозможность добавить книгу с пустным названием
3. Книгу можно добавить в коллекцию, если в ее названии более 0 симолов и не более 40 символов
4. Невозможно добавить книгу, у которой название состоит из более чем 40 символов
5. Невозможно добавить книгу в коллекцию, если в коллекции уже есть книга с таким названием


##Тесты для метода set_book_genre
Этот метод отвечает за установку жанра книги.
При проверке этого метода были реализованы следующие сценарии:
1. При добавлении книги в коллекцию ее жанр устанавливается корректно
2. Невозможно установить жанр для несуществующей книги
3. У существующей книги возможно изменить жанр на другой валидный жанр
4. У существующей книги невозможно изменить жанр на невалидное значение 

##Тесты для метода get_book_genre
Метод отвечает за вывод жанра книги по ее имени.
Проверки для данного метода следующие:
1. Возможно получить жанр книги, если эта книга существует у нее был задан жанр
2. Невозможно получить жанр у существующей книги, если этот жанр не задан изначально

##Тесты для метода get_books_with_specific_genre
Метод отвечает за вывод книг в определенном жанре.
Были реализованы следующие проверки для данного метода:
1. Можно получить книги с определенным жанром (проверка с двумя книгами с заданным жанром)
2. Невозможно получить список книг с заданным жанром, если изначально нет книг с таким жанром

##Тесты для метода get_books_genre
Данный метод отвечает за вывод текущего словаря.
Были проведены следующие проверки:
1. Если книги не добавлены, возвращаем пустой словарь
2. Если была добавлена 1 книга без жанра, то в словаре будет содержаться запись с названием этой книги, а жанра не будет

##Тесты для метода get_books_for_children
Данный метод возвращает книги, которые подходят детям.
Были реализованы следующие проверки:
1. Метод возвращает список книг, подходящих для детей, когда добавлена книга с детским жанром

##Тесты для метода add_book_in_favorites
Данный метод добавляет книгу в избранное.
Было проверено следующее:
1. Метод добавляет книгу в Избранное, если книга существует в коллекции

##Тесты для метода delete_book_from_favorites
Данный метод удаляет книгу из избранного.
Были реализованы следующие проверки:
1. Метод удаляет книгу из Избранного, если книга присутствует в этом списке

##Тесты для метода get_list_of_favorites_books
Метод отвечает за получение спсика избранных книг.
Были проведены следующие проверки:
1. Метод возвращает список избранных книг, когда в этом списке есть книги

