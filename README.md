# CHANGELOG

### v 0.2.0

* Авторизация Вконтакте

### v 0.2.9

* Фикс серверных маршрутов. Теперь Create, Update, Read и Delete работают как нужно.
* Добавлена time-ago поддержка

### v 0.3.0

* Изменена модель пользователя
* Дата и время встречи теперь сохраняются в одну запись
* Изменено диалоговое окно на bootstrap
* Исправлено изображение профиля пользователя для ВК

### v 0.3.1

* Корректное изображение профиля для ФБ и ВК
* Отображение друзей ВК
* Изменен single meeting

### v 0.4

* Добавлены комментарии к сообщениям
* Корректное отображение кнопок присоединиться и отклонить
* Корректный рефреш после запросов к API
* Рефакторинг серверной маршрутизации

### v 0.4.5

* добавлены грант таски для dev environment
* изменения страницы профиля: можно выбирать изображение и имя из любой соцсети
* добавлена возможность удаления аккаунта с удалением встреч и комментариев
* Получение текущего пользователя аякс запросом
* Добавлены маршруты для 404 и 500 ошибок
* Добавлен нод инспектор и линт

### v 0.4.6

* авторизация теперь проверяет емейл
* редактировать профиль - тестовый выбор изображения
* рефакторинг сервисов
* ejs шаблонизация

### v 0.4.7

* клик по карте заменен на дабл-клик
* дизайн карты, иконок и всплывающих окон
* подключен винстон логгер
* добавлены иконки категорий
* двуязычные названия категорий

### v 0.5.0

* карта запускается и позиционируется без геолокации
* socket io, real time обновление митингов и комментариев

### v 0.5.1

* Уведомления о приглашениях
* Сообщения
* Страница сообщений

### v 0.5.2

* Переход на Sass
* populated embedded documents (comments и notifications содержат ссылку на пользователя и митинг)
* кнопки участвовать и отклонить приглашение в уведомлениях, и на странице сообщений
* добавление события на карте теперь происходит после нажатия на плюсик, когда курсор меняет вид на прицел, или по дабл клику
* выход из режима добавления события - по кнопке escape
* angular toastr для всплывающих сообщений, нужна доработка

### v 0.5.3

* большое фото профиля вконтакте
* исправлен баг с некорректной валидацией аккаунта при входе через ВК
* подключен travis ci
* Удаление уведомлений

### v 0.5.4

* Сверху отображаются только "непрочитанные" уведомления
* Отображение событий только в пределах определенного радиуса
* Фильтры на карте (мои события, друзья, приглашения и принятые приглашения)
* Исправлена ошибка с отклонением приглашения, теперь пользователь корректно удаляется из массива invitedUsers







