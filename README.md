# ДЗ

## Как делать:

1. Перед выполнением сделайте мердж мастера моего репозитория себе в форк (чтобы иметь актуальный код);
2. Создайте ветку для выполнения ДЗ;
3. Выполните ДЗ в этой ветке;
4. Сделайте Pull Request этой ветки на мастер моего репозитория;
5. Напишите мне (a.koretskiy@javascript.info) письмо со ссылкой на PR.

Дедлайн – 21:00 по Москве/Киеву за день до занятия.

## HT1

1. Создать компоненту Reviews, где выводить отзывы про рестораны и рейтинг с помощью компоненты Rate https://ant.design/components/rate/#header.
2. Создать компоненту Restaurant, где показывать Menu и Reviews.
3. В компоненте Restaurant показывать средний рейтинг с помощью компоненты Rate https://ant.design/components/rate/#header
4. (опционально) Украсить приложени с помощью компонентов из ant.design.

## HT2

1. Покрыть PropTypes все компоненты.
2. Написать тесты на уменьшение блюд.
3. Покрыть тестами Reviews.

## HT3

1. Сделать компонент Order в котором отображать выбранные товары с их количеством, суммоый по каждому товару и общей стоимостью заказа.
2. Сделать у каждой позиции в этом заказа кнопки +/-/удалить (при нажатии на удалить удаляеься все количество товара)

## HT4

1. Переписать review и рестораны на key=>value
2. Починить отображение review (добавить пользователя из normalizedUsers в редьюсер reviews)
3. Сделать форму добавления нового review
4. Написать middleware для генерации uuid
5. Реализовать добавление review в стор и показывать его

## HT5

1. Загрузить продукты через api middleware
2. Загрузить users через redux-thunk
3. Полностью убрать fixtures из приложения, все грузить с сервера
4. При загрузках показывать лоареры, все грузить максимально низко, там где эти данные нужны
5. При желании переписать все на immer/immutable

## HT6

1. Сделать роутинг на menu and reviews (/restaurants/id/reviews)
2. В корзине продукты сделать ссылками на их рестораны

## HT7

1. Сделать редирект со корня и с /restaurants на страницу ресторана
2. Проверить если мы на /checkout, то при нажатии на кнопку:

- отправить запрос на: '/api/order'
- блокировать кнопку на время запроса (можно добавить лоадер)
- при успешном ответе редиректить на новую страницу "Спасибо за заказ!"

3. Реализовать переключение валюты, хранить словарь словарь в контексте
4. Анимировать добавление ревью
