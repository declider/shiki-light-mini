# Сильно урезанная тема для shikimori.

Цель - создать светлую тему, где не будет ничего лишнего для людей использующих shikimori только для "менеджмента" аниме/манги/ренобэ и не интересующихся любой социальной активностью на сайте. Если вам хоть немного интересны профили других людей или подобные социальные функции - тема Вам **не подойдёт**.

Основой послужила тема от [Kotiaa](https://github.com/Kotiaa/shiki-light).

# Изменения:
1. Весь шрифт переведён в Roboto от гугла.
2. В шапке вырезаны название сайта, иконки почты и форума.
3. В меню сверху скрыты все пункты кроме Аниме/Манга/Ренобэ (было 14 пунктов и 4 названия групп, осталось 3 пункта и 0 названий групп).
4. В меню аккаунта скрыты пункты про достижения, почту и клубы.
5. Скрыта кнопка "сообщить об ошибке".
6. Скрыт заголовок "никнейм / назад / профиль" в профиле.
7. Скрыта вся правая панель фильтрации в профиле, список произведений расширен горизонтально (при поиске произведений фильтрация осталась).
8. Скрыта вся правая панель информации о клубах/избранном/озвучках/... на странице произведения.
9. Скрыты кнопки "комментировать, написать отзыв, оставить рецензию, редактировать" на странице произведения.
10. Скрыты кнопки "смотреть онлайн на ..."
11. Скрыт футер.
12. Скрыт значок медали около наград на странице произведения.
13. Скрыт автор описания для тайтла на странице произведения.
14. В профиле скрыты друзья, клубы, статистика по времени.
15. Картинки масштабируются немного иначе.

# Установка:
Настройки > Внешний вид сайта > Стили сайта CSS > В текстовую область CSS вписать
```css
@import url('https://raw.githubusercontent.com/declider/shiki-light-mini/master/shiki-light-theme.css');
```
и сохранить.

Если нужно что-то подредактировать - весь css тут есть, вместо импорта копируете всё содержимое css файла.

# Баги которые когда-нибудь да будут пофикшены:
- На главной странице иногда проскакивают плохие цвета.
- Кое-где остался заголовок "комментарии" хотя сами комментарии не отображаются.
- Избранное выглядит не очень приятно.
