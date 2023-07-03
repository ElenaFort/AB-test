# AB-test
## Урок 1. Формирование гипотез и их скоринг на основе данных
### Задание 1 . Выберите любой продукт.
Например ваш продукт:
- ozon.ru
- citilink.ru
- telegram

Какие бы ключевые метрики вы выделили? Опишите почему вы выбрали именно их и можно ли их измерить

### Задание 2. Сформулируйте 5-10 гипотез для выбранного продукта.

## Урок 2. А/Б тестирование
### Задание 1.
**Сделайте приоритезацию гипотез из предыдущего урока с помощью ICE**

### Задание 2.
**Составьте шаблон дизайна эксперимента для гипотезы, которая набрала больше всего баллов в практическом задании предыдущего урока**

## Урок 3. A/B-тестирование веб-приложений

Настроить а/б тест на сайте с 3-мя изменениями https://telegram-feedback.com/</br>
Добавьте любые 2-3 изменения (инструкция: https://blog.click.ru/growthhacking/google-optimize-kak-testirovat-ux-sajta-bez-programmista/#h2_2)</br>
Создайте контейнер в Гулг Аналитике (инструкция: https://blog.click.ru/analytics/kak-nastroit-google-analytics/)</br>
Создайте контейнер для тегов (Как показанно в лекции, есть инструкция в методичке опуионально, главное просто увидеть принцип)</br>
Укажите все настройки в Оптимизации</br>

В качетсвет ответа прикрепите отчёт. В отчёт вставляйте скриншоты выполнения шагов и небольшие пояснения.</br>
Главная зада - понять концепцию проведения подобных эксперементов, через Гугл Оптимизацию! Поэтому просто фиксируем основные моменты (посмотрите финал семинара, там объясняю этот момент подробнее).

## Урок 4. A/B-тестирование мобильных приложений

Настроить а/б тест на сайте с 2-мя изменениями на своем сайте либо на аккаунте преподавателя(доступ по запросу)

- уведомления
- remote config
- in-app сообщения

## Урок 5. Применение математической статистики для проверки гипотез в реальной жизни для популярных метрик

### Задание 1.
**Вы провели эксперимент c упрощением формы заказа в магазине Утконос и получили результаты по метрике конверсий в покупку. Выберите метод оценки и оцените есть ли стат.значимые различия между конверсиями в двух группах при alpha = 5%. Дайте краткие рекомендации команде.**

**Результаты:** 

1. Число юзеров в группах , которые заходили на сайт в период эксперимента: n1 = 15550 и n2 = 15550 .
2. Число юзеров в группах , которые совершили хотя бы одну покупку за период эксперимента: n1 = 164 и n2 = 228
3. Конверсии : conv1 = 1.05% conv2 = 1.47% .

### Задание 2.
**Сравниваем метрику конверсия в покупку. Размер выборки - 10000 элементов в каждой группе . Какой статистический критерий тут лучше всего подойдёт и почему?**

## Урок 6. Расчёт длительности А/B теста + продвинутые топики
### Задание1.
Продакт на главной mail.ru решил протестировать в рекомендательной ленте контента вместо карточек со статьями видеоплеер с короткими видео. Нынешний таймспент на юзера в день в среднем равен 25 минут, а стандартная ошибка (SD) равна 156. Мы предполагаем, что в новой версии таймспент на юзера в день изменится на 10%. Средний трафик 20000 человек в день. Посчитайте сколько дней необходимо держать эксперимент при alpha = 5% и beta = 20% .
### Задание 2.
Наша продуктовая команда в ecommerce магазине планирует запустить тест, направленный на ускорение загрузки сайта. Одна из основных метрик bounce rate в GA = 40%. Мы предполагаем, что при оптимизации сайта она изменится минимум на 20%.Средний трафик 4000 человек в день. Посчитайте сколько нам нужно дней держать эксперимент при alpha = 5% и beta = 20%
