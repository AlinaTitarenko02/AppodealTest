# AppodealTest
Зарегистрируйтесь в www.appodeal.com и загрузите Appodeal SDK для Android или iOS. Создайте приложение в которое нужно интегрировать Appodeal SDK. Приложение должно содержать активити с несколькими кнопками по центру экрана:
1) Кнопка Banners: при нажатии на кнопку будут появляться баннеры сверху (BANNER_TOP). На время показа других типов рекламы, необходимо скрывать баннеры. После показа 5 баннеров необходимо скрыть этот тип рекламы
 
2) Кнопка Interstitials: При нажатии на кнопку будут отображаться interstitial. Показывать interstitials не чаще чем раз в минуту. Когда показ сделать невозможно, кнопка должна быть не активной.
3) Кнопка Rewarded Video должна быть активна только при наличии загруженного rewarded video. За одну сессию нельзя показать больше 3х rewarded video. Когда показ сделать невозможно, кнопка должна быть не активной.
4) Кнопка Native: При нажатии на кнопку будет появляться ListView / UITableView со встроенной нативной рекламой (не менее 3 штук).
При разработке необходимо учесть, что экран может меняться как в portrait, так и в landscape ориентацию. Можно использовать тестовый режим (test mode) для отображения рекламы.
Итогом работы должен быть Android или iOS проект (и если Android проект, то + apk приложения). Проект залить в приватный репозиторий на github. Оформить Readme на github. Предоставить доступ для пользователей aimock
