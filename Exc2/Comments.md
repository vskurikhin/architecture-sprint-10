# Данные
- Персональные данные пользователя хранятся в Базах Данных (SQL и S3).

# Уничтожение конфиденциальных данных
- По запросу пользователя данные будут удалены.

# Способы защиты данных
- Персональные данные пользователя хранятся в Базах Данных в зашифрованном виде.
- Каждому пользователю присваивается токен в системе.
- Администратор рецепшен не имеет полного доступа к базе пользователей, только к минимальному набору.
- Доктор получает доступ к данным пациента только на время приема.
- Устаревшие данные автоматически архивируются.
