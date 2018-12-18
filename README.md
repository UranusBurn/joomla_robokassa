Инструкция по установке и настройке  плагина Robokassa для Virtuemart 3.4.x

###Установка
1. Установка плагина выполняется с zip архива, как и любой другой плагин для CMS Joomla.
1. Для этого заходим в административную панель магазина в раздел Расшерения – Менеджер расширений – Установка.
1. Выбираем архив плагина.

###Настройка
1. В личном кабинете Robokassa Вам необходимо указать настройки:
	- Алгоритм расчета хеша: md5
	- Result URL : http://ваш_магазин.ru/index.php? index.php?option=com_virtuemart&view=pluginresponse&task=pluginnotification&tmpl=component
	- Success URL : http://ваш_магазин.ru/index.php? option=com_virtuemart&view=pluginresponse&task=pluginresponsereceived
	- Fail Url : http://ваш_магазин.ru/index.php? option=com_virtuemart&view=pluginresponse&task=pluginUserPaymentCancel
	- Метод отсылки данных во всех случаях POST.

1. Далее проходим в административную панель магазина на Virtuemart и добавляем новый способ оплаты. Для этого пройдите в раздел Virtuemart – Магазин – Способы оплаты.

1. Жмем на панели сверху Создать.
 
1. И добавляем новый способ оплаты как изображено на скриншоте ниже. Обязательно в поле Способ оплаты нужно выбрать Robokassa и Опубликовано – Да (если необходимо отображать способ оплаты на этапе оформления заказа). Все остальные поля на Ваше усмотрение. 
1. Жмем Сохранить. Далее переключаемся на вкладку Конфигурация.
1. Заполняем обязательные поля в разделе Технические настройки (данные берем с личного кабинета Robokassa):
	- Идентификатор магазина 
	- Пароль 1
	- Пароль 2
1.	Если Вы используете тестовые данные – не забудьте переключить настройку Среда на Тестовая.
1. Подтверждаем настройки нажатием кнопки Сохранить.
1. Настройка завершена.
