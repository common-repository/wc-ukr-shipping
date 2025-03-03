=== WC Nova Poshta Shipping - Integration of Nova Poshta delivery service for WooCommerce ===
Contributors: kirillbdev
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl.html
Tags: nova poshta, нова пошта, доставка, shipping, woocommerce
Requires PHP: 7.4
Tested up to: 6.6
Stable tag: 1.12.7

Simple and comfortable plugin for connect Nova Poshta delivery service to your WooCommerce store.

== Description ==

**Simple and comfortable plugin for connect Nova Poshta delivery service to your WooCommerce store.**

[Documentation](https://kirillbdev.pro/docs/wcus-base-setup/)
[PRO version](https://kirillbdev.pro/wc-ukr-shipping-pro/)

== Installation and setup tutorial ==

https://www.youtube.com/watch?v=IFW0B75s54o

== Features ==

* Simple and intuitive setup
* Ability to select Nova Poshta warehouse or poshtomat on checkout page
* Ability to setup fixed shipping cost
* Ability to calculate cost without adding it to order total
* Integration with popular plugins for localization: WPML and Polylang
* Support latest versions of Wordpress and WooCommerce
* Support WooCommerce geo zones

== PRO version ==

WC Ukraine Shipping PRO has additional premium features that helps you to optimize work with your clients

* Full address shipping integration (using Nova Poshta address API)
* Automatic calculation of shipping costs (via Nova Poshta API)
* Shipping costs calculation based on order total
* Ability to separate cost calculation for address shipping
* Ability to generate TTN for all types: W2W, W2D, D2W, D2D
* Ability to mass generation of TTN in one click
* Print TTN of all types: A4, 85x85, 100x100 (zebra)
* Automatic email notifications after generating TTN
* Automatic sms notifications after generating TTN (need extra addon)
* Cloud features (Tracking, Performance address API)
* [Automation] No-code business-processes constructor
* Premium support

[Buy PRO version](https://kirillbdev.pro/wc-ukr-shipping-pro/)

== Installation ==

= Minimum Requirements =

* PHP 7.4 or greater is recommended
* MySQL 5.7 or greater is recommended

= Automatic installation =

Automatic installation is the easiest option as WordPress handles the file transfers itself and you don’t need to leave your web browser. To do an automatic install of WooCommerce, log in to your WordPress dashboard, navigate to the Plugins menu and click Add New.

In the search field type “WC Ukr Shipping” and click Search Plugins. Once you’ve found it you can view details about it such as the point release, rating and description. Most importantly of course, you can install it by simply clicking “Install Now”.

= Manual installation =

The manual installation method involves downloading this plugin and uploading it to your webserver via your favourite FTP application. The WordPress codex contains instructions on how to do this here.

= Updating =

Automatic updates should work like a charm; as always though, ensure you backup your site just in case.

== FAQ ==

= Does plugin supports WooCommerce checkout blocks? =

Unfortunately plugin doesn't support WC checkout blocks yet.

== Changelog ==

= Version 1.12.7 / (24.10.2024) =
* Architecture improvements.
* Checked compatibility with latest Wordpress and WooCommerce versions.

= Version 1.12.6 / (04.10.2024) =
* Checkout process and performance improvements.
* Added new option "Calculate shipping cost view only". Allows you to calculate shipping rates but without adding it to order total.
* Checked compatibility with latest Wordpress and WooCommerce versions.

= Version 1.12.5 / (12.09.2024) =
* [Feature] Migration mechanism V2.
* Checked compatibility with latest Wordpress and WooCommerce versions.

= Version 1.12.4 / (29.06.2024) =
* [Fix] Removed extra slashes when saving shipping address.
* Checked compatibility with latest Wordpress and WooCommerce versions.

= Version 1.12.3 / (26.04.2024) =
* Divided search of warehouses and poshtomats.
* [New UI] Saving Nova Poshta area when order placed.
* Some localization improvements.
* Checked compatibility with latest Wordpress and WooCommerce versions.

= Version 1.12.2 / (02.03.2024) =
* [Fix] Broken ukrainian localization.
* [Feature] Trimming spaces for search cities/warehouses query.
* Checked compatibility with latest Wordpress and WooCommerce versions.

= Version 1.12.1 / (19.10.2023) =
* Added HPOS support.

= Version 1.12.0 / (09.07.2023) =
* Improved warehouse data loading performance.
* [Checkout old] Removed country check as required condition for show shipping fields.
* Checked compatibility with latest Wordpress and WooCommerce versions.

= Version 1.11.3 / (25.09.2022) =
* Improved integration with migration plugins.
* Improved plugin localization.

= Version 1.11.2 / (07.06.2022) =
* Remove old files from vcs.

= Version 1.11.1 / (07.06.2022) =
* Плановые улучшения кодовой базы.
* Плановые улучшения производительности.

= Version 1.11.0 / (08.04.2022) =
* Минимальная версия PHP увеличена до 7.4
* Новый UI теперь включен по-умолчанию для всех новых магазинов.
* Улучшено описание некоторых настроек.
* Проведены мелкие улучшения производительности.

= Version 1.10.0 / (12.12.2021) =
* Плановые улучшения и переработки кодовой базы.

= Version 1.9.1 / (29.09.2021) =
* Мелкие исправления.

= Version 1.9.0 / (29.09.2021) =
* Обновлен модуль загрузки отделений (аналогичен PRO версии).
* Восстановлена опция сохранения последнего отделения (работает только с новым UI).
* Улучшена синхронизация данных на странице оформления заказа (новый UI).
* Улучшения архитектуры и кодовой базы.

= Version 1.8.2 / (01.08.2021) =
* Backend UI rework.

= Version 1.8.1 / (01.08.2021) =
* Улучшена отзывчивость нового UI на мобильных устройствах.
* Увеличен базовый таймаут запросов к API Новой Почты до 15 секунд.
* Интеграция работы опции "Включить блок Адресной доставки" для нового UI.

= Version 1.8.0 / (16.06.2021) =
* Внедрен новый UI для страницы оформления заказа (включается во вкладке Общие). Подробное описание его работы: https://kirillbdev.pro/wcus-pro-new-ui-110/
* Добавлена новая вкладка Доставка для страницы настроек (для более логического разделения настроек).
* Добавлен фильтр wcus_checkout_i18n (будет описан в документации).
* Core update.

= Version 1.7.7 / (17.05.2021) =
* Исправлена ошибка при загрузке областей на странице оформления заказа.

= Version 1.7.6 / (16.05.2021) =
* Core update.

= Version 1.7.5 / (07.05.2021) =
* Основная логика была вынесена в отдельное ядро (которое также используется для PRO версии).
* Добавлен фильтр wcus_checkout_validation_active. С помощью него можно отключить валидацию полей плагина на странице оформления заказа.
* Добавлен фильтр wcus_dynamic_shipping_label (будет описан в документации).
* Теперь для корректной работы плагина требуется PHP не ниже версии 7.0.
* Улучшения безопасности и производительности.

= Version 1.7.4 / (05.02.2021) =
* Исправлена ошибка сохранения адреса доставки на украинском языке, даже если в настройках выбран русский.
* Добавлена опция "Показывать почтоматы" (включена по-умолчанию).
* Добавлен фильтр wcus_get_areas.
* Улучшения локализации админ-части.
* Общие улучшения производительности.

= Version 1.7.3 / (24.12.2020) =
* Исправлены некоторые несовместимости с PHP8.
* Добавлен фильтр: wcus_http_post_timeout. Позволяет увеличить таймаут опроса API при загрузке отделений.

= Version 1.7.2 / (11.12.2020) =
* Исправлен некорректный вывод названия доставки, если оно содержит кавычки.
* Добавлен вывод стоимости доставки на странице корзины.
* Исправлены некоторые ошибки несовместимости с плагином Saphali Woocommerce.
* Добавлена локализация сообщения о незаполненных данных Новой Почты.

= Version 1.7.1 / (29.09.2020) =
* Исравлен баг, когда плагин при любом выбранном методе доставки добавлял свою стоимость к итоговой сумме заказа.

= Version 1.7.0 / (06.09.2020) =
* Глобальные работы по оптимизации кода (улучшения скорости работы, удаление старого и ненужного кода).
* Полная смена логики сохранения заказа (по аналогии с PRO версией).
* Новые возможности для расширения расчета стоимости доставки (по аналогии с PRO версией).
* Убрана настройка "Сохранять последнее отделение пользователя" (в связи с подготовкой нового функционала).
* Убрана кнопка "Наш сайт" с верней панели настроек.
* Новая, улучшенная обработка ошибок, которые могут возникать при первоначальных настройках плагина (вывод ошибок API, ошибок доступности API).

= Version 1.6.3 / (09.05.2020) =
* Корректировка вывода верстки на странице оформления заказа.

= Version 1.6.2 / (09.05.2020) =
* Небольшие исправления подгрузки переводов.

= Version 1.6.1 / (09.05.2020) =
* Интеграция локализации отделений (русский и украинский) с плагином Polylang.
* Внедрена опция "Использовать новые UI компоненты". По-умолчанию эта опция включена. Опция должна решить частую проблему несовместимости с плагином WooCommerce Checkout Manager.
* Блок выбора отделения доставки теперь функционирует как для billing секции, так и для shipping (доставка по другому адресу) секции. Следовательно, теперь плагин пишет данные адреса заказа в одну из этих секций.
* Исправлены некоторые мелкие баги, а также проведен плановый рефакторинг кодовой базы.

= Version 1.6.0 / (22.04.2020) =
* Исправлена ошибка монопольной установки отделения Новой Почты, даже, если для заказа выбран другой способ доставки.
* Теперь поле произвольного адреса не убирает выбор области и города (соответственно, для адресной доставки эти поля теперь необходимы к заполнению).
* Сохранение последнего отделения доставки для пользователя теперь можно опционально отключить в настройках плагина.
* Добавлена CSRF защита на странице оформления заказа.
* Добавлены базовы файлы переводов для 3-х языков (русский, украинский, английский). Домен локализации: wc-ukr-shipping-l10n
* Добавлена настройка выбора типа переводов, которые будет использовать плагин (из mo файлов или из вкладки "Переводы"). Соответственно, улучшилась интеграция с плагинами переводов типа WPML, Polylang. Если ваш сайт не имеет языковых версий, то значение данной настройки можно оставить без изменений. Если же у вас несколько языковых версий, то установите значение опции в "из mo файлов". Это даст возможность получить переводы для 3-х базовых языков. Также, с помощью соответствующих плагинов (например WPML String Translations), вы сможете изменять данные переводы (домен локализации плагина: wc-ukr-shipping-l10n).
* Добавлен перевод для пустого результата поиска в полях выбора области / города / отделения (ранее был "No results found").
* Добавлена автоматическая интеграция языка отделений (русский, украинский) с плагином WPML.

= Version 1.5.2 / (09.01.2020) =
* Исправлена ошибка, при которой в поле выбора области дублировались все значения.
* Улучшен алгоритм сортировки результатов при поиске города. Теперь, при вводе в поле поиска, например, строки "Кие", первым в списке городов будет доступен Киев (как наиболее подходящий под запрос), а уже после - все прилегающие пгт и села Киевской области.
* Также улучшен алгоритм сортировки результатов при поиске отделений. Почти любое отделение теперь можно найти, введя нужную цифру.
* Данные улучшения также внедрены в Premium версию.

= Version 1.5.1 / (06.01.2020) =
* Добавлена новая опция на странице настроек "Позиция блока на странице оформления заказа". Опция позволяет задать позицию блока выбора отделения в основной (по-умолчанию) или дополнительной секции. Положение блока в дополнительной секции актуально для тем, в которых поля оформления заказа расположены в две колонки. Таким образом данная опция придаст вашей странице оформления заказа более красивый вид.
* Проделана мелкая работа над UI страниц настроек.
* Проделана работа над функционалом, позволяющая более качественно интегрировать данные бесплатной версии плагина с Premium, при переходе на Premium.

= Version 1.5.0 / (04.01.2020) =
* Исправлена ошибка вызова несуществующей функции.
* Исправлена ошибка, когда удалялись все данные из базы отделений при деактивации плагина.
* Удаление ненужного функционала, а также некоторые мелкие исправления кода.
* Теперь выбор отделения доставки сохраняется за пользователем.
Для авторизованых клиентов срок хранения выбора - вечность, для гостей - в пределаж жизни сессии WooCommerce.
* PRO версия доступна для покупки.

= Version 1.4.5 / (19.10.2019) =
* Исправлена ошибка парсинга js скриптов в браузере Internet Explorer.
* Пункт настроек в меню админ-панели теперь имеет стандартные стили Wordpress.
* Информация про адрес доставки теперь также записывается в данные о плательщике (billing_state, billing_city, billing_address_1).

= Version 1.4.4 / (16.10.2019) =
* Исправлена ошибка локализации отделений.

= Version 1.4.3 / (10.10.2019) =
* Временный отказ от REST Api в пользу обычного ajax.
* Переделана страница настроек плагина.
* Польностью переделана локализация. Более подробнее вы можете прочитать в документации.
* Страница настроек теперь вынесена из меню WooCommerce и расположена в главном меню Wordpress (как раньше).
* Исправлены мелкие некритичные ошибки.

= Version 1.4.2 / (27.08.2019) =
* Фикс. проверки на несуществующий параметр в REST ответе.
* Функционал корректного удаления плагина.

= Version 1.4.1 / (25.08.2019) =
* Перенос функционала сокрытия стандартных полей (город, область, почтовый индекс и адрес) на front-end.

= Version 1.4.0 / (24.08.2019) =
* Исправлен редкий баг, когда инициализация UI для полей Новой Почты (select 2) происходила раньше, чем будут загружены области доставки.
* Теперь плагин будет работать даже с выключенным REST Api (тип работы, rest или wp-ajax, определяется автоматически при анализе возможностей сайта).
* Теперь плагин по-умолчанию скрывает стандартные billing поля (город, область, почтовый индекс и адрес). Для того, чтобы отменить данную функцию, Вам необходимо передать значение false в фильтр wc_ukr_shipping_prevent_disable_default_fields.
* Добавлена ссылка на страницу настроек в разделе плагинов.
* Удалены донаты в связи со скорым выпуском PRO версии.

= Version 1.3.0 / (26.07.2019) =
* Русифицированы георгафические области при выборе русского языка в настройках.
* Введен базовый модуль репортов для отправки анонимной статистики (работает только, если включена соответствующая настройка в опциях плагина).
* Страница настроек плагина была перенесена и теперь стала подпунктом меню Woo Commerce.

= Version 1.2.0 / (24.06.2019) =
* Исправлена ошибка, когда при выборе другого способа доставки, не выводился блок "Доставка по другому адресу" (Shipping Fields).
* Теперь плагин работает даже если вы скрыли или удалили поле страна (billing_country), используя сторонний плагин или код.
Стоит заметить, что плагин все также работает только с зоной UA.
* Теперь каждое строковое поле, которое нельзя изменить через страницу настроек (например, "выберите область"), выводится через функцию __().
Данное изменение позволяет вам изменить эти поля с помощью одного из известных плагинов локализации, например WPML.

= Version 1.1.2 / (19.06.2019) =
* Исправлена ошибка, когда пропадала область доставки при изменении заказа из админ-панели.

= Version 1.1.1 / (19.06.2019) =
* Исправлена ошибка запросов на несуществующие REST точки из front-end, если сайт находится не в корневом каталоге сервера (спасибо пользователю @myideasforsite).
* Добавлена опция сокрытия блока адресной доставки.
* Добавлена сортировка отделений по номерам во front-end (выполните миграцию в настройках, затем обновите информацию об отделениях).

= Version 1.1.0 / (16.06.2019) =
* Добавлена порционная загзука городов и отделений, для снятия ограничений по оперативной памяти хостинга.
Теперь плагин работает даже на хостингах с 64МБ ОЗУ.
* Создан абсолютно новый интерфейс настроек плагина. Все опции теперь вынесены в одну удобную форму.
Настройки теперь расположены по адресу yoursite.com/wp-admin/admin.php?page=wc_ukr_shipping_options
* Добавлен функционал миграций версий для безопасного обновления структур данных плагина до актуальной версии.
Функционал доступен на странице настроек.
* Теперь вам нужен API ключ для обновления данных Новой Почты. Настройка также находится по адресу yoursite.com/wp-admin/admin.php?page=wc_ukr_shipping_options
* Добавлена опция выбора языка, на котором будут подтягиватся данные о городах и отделениях Новой Почты.
Для работы настройки вам понадобится мигрировать данные до актуальной версии и обновить данные об отделениях Новой Почты. Все опции доступны на странице настроек.
* Добавлена опция выбора цвета спинера загрузки во front-end
* Добавлена опция смены названия метода во front-end, а также опция смены названия для поля "Адресная доставка"

= Version 1.0.2 / (07.06.2019) =
* Исправлена ошибка некорректной кодировки для таблиц плагина
* Добавлен WP Rest Api
* Исправление 500 ошибки сервера у некоторых пользователей на странице оформления заказа

= Version 1.0.1 / (07.06.2019) =
* Исправлена ошибка, когда скрипты плагина подтягивались на все страницы сайта.
* Добавлена проверка на внутренние ошибки сервера при выборе адреса доставки с выводом их на экран.
* Добавлено версионирование скриптов.

= Version 1.0.0 / (03.06.2019) =
* Initial