# Project-Mesto-
собрание частей учебного проекта "Место"

## Обзор
Данный учебный проект представляет собой web-приложение (SPA - single page application), в котором представлен набор постов пользователей, содержащих превью фотографии, ее название и количество лайков. Каждую фотографию можно посмотреть в увеличенном варианте. Приложение является адаптивным и может отображаться на устройствах с различными разрешениями экранов, начиная с ширины экрана 320 px (смартфоны) и до больших мониторов. Максимальная ширина страницы 1440 px. 
###  Основной функционал:
 - редактирование профиля пользователя (Имя, описание, аватар),
 - загрузка списка постов с сервера;
 - добавление/удаление нового поста с фотографией места (пользователь может удалять только свои посты),
 - просмотр изображения в оригинальном размере,
 - возможность отмечать посты лайком.
### Как устроен сайт
Для входа в приложение необходимо быть зарегистрированным и авторизованным на сервере. Поэтому в приложении есть маршруты на соответствующие формы регистрации и аутентификации пользователя.  
Структура основной страницы очень простая:
 - шапка
 - профиль пользователя
 - сетка постов
 - подвал
 - попапы редактирования данных пользователя, смены аватара, добавления нового поста, подтверждения удаления поста и просмотра картинки в оригинальном размере.  
 
В профиле пользователя размещены аватар, имя пользователя, его описание и кнопка добавления нового поста.  
  
Данные пользователей и карточек с фотографиями хранятся на сервере в базе данных.  
### Используемые технологии
Фронтенд приложения реализуется на React.js, HTML5, CSS3, JS(ES 6+). Приложение развернуто с помощью CRA (create react application).
Бэкенд создается с помощью Node.js, Express.js, MongoDB.

## Этапы реализации проекта



