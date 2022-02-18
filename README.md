# job4j_forum

В качестве проекта мы сделаем классическое приложение - форум.

Создадим отдельный репозиторий job4j_forum.

Forum - Это учебный проект. Главная страница - список тем форума.

Добавил Spring boot.

Создал виды и контроллеры.

index.jsp - список тем.

reg.jsp - регистрация пользователя.

login.jsp - авторизация пользователя.

edit.jsp - создание и редактирование темы.

post.jsp - тема и обсуждения.

Так же создал модели Post, User.

Неавторизованные пользователи могут прочитать только список тем форума, зарегистрироваться и авторизироваться. Остальные операции им недоступны.

Авторизованные пользователи могут добавлять темы, открыть список сообщений любой темы, изменять свои сообщения и темы, удалять свои сообщения.

Чтобы создать или изменить тему нужно создать/изменить ее первое сообщение, поскольку тема задается именно первым сообщением.