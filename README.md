# QA Portfolio — Айса Атюева

Я Manual QA Engineer с коммерческим опытом тестирования мобильной игры на Android и iOS и web-проектов.

В этом репозитории собраны обезличенные примеры моей тестовой документации:

- чек-листы;
- баг-репорты;
- API-проверки;
- примеры анализа дефектов.

Основные направления:

- Game QA
- Mobile testing
- Web testing
- API testing
- E-commerce testing
- Payment testing

Инструменты:

- DevTools
- Bruno API Client
- Postman
- TeamCity
- Android / iOS logs
- SQL — базовый уровень
- JSON / XML

Реальные данные проектов, внутренние ссылки, токены, cookies и пользовательские данные не раскрываются.
## Содержание

### Checklists

- [Чек-лист тестирования оплаты](checklists/payment-checklist.md)
- [Чек-лист регресса поиска, фильтров и сортировки](checklists/search-filters-regression-checklist.md)
- [Чек-лист тестирования раздела “Избранное”](checklists/favorites-checklist.md)
- [Чек-лист тестирования корзины](checklists/cart-checklist.md)
- [Чек-лист тестирования личного кабинета](checklists/account-checklist.md)

### Bug reports

- [502 Bad Gateway при создании платежа после включения проверки чеков](bug-reports/payment-create-502-after-receipt-check.md)
- [После возврата с платежной страницы отображается страница успешного оформления заказа](bug-reports/unsuccessful-payment-success-page.md)
- [При серверных ошибках отображаются сообщения о неверных пользовательских данных](bug-reports/server-errors-wrong-user-message.md)
- [Стоимость доставки не учитывается в итоговой сумме оплаты](bug-reports/delivery-cost-not-included-in-payment.md)
- [При самовывозе в сумму оплаты добавляется стоимость доставки после исправления расчета курьерской доставки](bug-reports/pickup-payment-includes-delivery-cost-after-fix.md)
- [Лишний экран перед авторизацией и разное поведение перехода в личный кабинет](bug-reports/profile-login-extra-step-inconsistent-navigation.md)
- [Недоступный товар в корзине не помечается как “Нет в наличии” и блокирует оформление заказа](bug-reports/out-of-stock-item-blocks-checkout.md)
- [Выход из аккаунта на одном устройстве завершает сессии на других устройствах](bug-reports/logout-invalidates-other-sessions.md)
- [Корзина не привязана к аккаунту и не синхронизируется между устройствами](bug-reports/cart-not-synced-between-account-and-devices.md)
- [Длинный email не помещается в контейнере и ломает отображение профиля](bug-reports/long-email-breaks-profile-layout.md)

### API testing

- [Чек-лист API-проверок интернет-магазина](api-testing/ecommerce-api-checklist.md)
- [Чек-лист API-проверок сессий и токенов](api-testing/auth-sessions-tokens-checklist.md)
- [Чек-лист API-проверок платежной интеграции](payment-integration-checklist.md)

### Analysis

- [Сравнение вариантов регистрации для интернет-магазина](analysis/registration-options-comparison.md)
- [Анализ требований к безопасности платежей и модели данных](analysis/payment-security-and-data-model.md)
- [Идея клиентского мероприятия для выбора названия магазина](client-event-store-naming.md)

## Примечание

Все материалы в портфолио обезличены.  
Цель репозитория — показать подход к тестированию, структуру проверок и умение оформлять тестовую документацию без раскрытия конфиденциальной информации.
