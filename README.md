# Что это?
Вы смотрите исходный код чат-движка используемого на сайте https://crawc.net.
Вы можете использовать его по своему усмотрению, и также Вам разрешается вносить любые правки в свою версию.

# Установка и настройка
Для того чтобы начать пользоваться моим кодом, вам будет необходимо установить node.js, затем npm, после чего поочередно установить все модули используемые в require. Далее загрузить структуру базы данных из structure.sql. Затем надо исправить основые конфигурации в srv.js и убедиться, что все патчи в контролерах для upload и uploadone соответствуют расположению корневого каталога чата на сервере. Затем сгенерируйте https ключи для сайта и укажите путь к ним в том же srv.js (для генерации ключей рекомендую использовать certbot).

# Обратная связь
При возникновении проблем с установкой или настройкой, обращайтесь ко мне через мой профиль на гитхабе или хабре - я отвечу на Ваши вопросы.
