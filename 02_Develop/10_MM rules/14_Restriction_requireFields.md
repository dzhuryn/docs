Описание
Виджет для плагина ManagerManager, позволяющий сделать поля документа или TV обязательными для заполнения. Добавляет звёздочку красного цвета рядом с именем обязательного для заполнения поля, выдаёт сообщение при попытке сохранить не заполнив обязательные поля, предотвращая сохранение.
Список изменений
Добавлена поддержка TV типа «email».
Документация
Для установки распакуйте архив в /assets/plungins/managermanager/widgets/. Смотрите также документацию ManagerManager 0.5.1 и модуль ddMMEditor.
Описание параметров
Название	Описание	Допустимые значения	Значение по умолчанию	Обязателен?
fields	Поля документа (или TV), которые должны быть обязательными.	{comma separated string}	—	true
roles	Роли, для которых необходимо применить виждет, пустое значение — все роли.	{comma separated string}	—	false
templates	Id шаблонов, для которых необходимо применить виджет, пустое значение — все шаблоны.	{comma separated string}	—	false
Примеры
Сделать обязательным для заполнения заголовки и даты публикации всех документов
mm_requireFields('pagetitle,pub_date');