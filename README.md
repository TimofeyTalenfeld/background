# yandex_lesson

## Задание 1

Загрузка списка изображений и склейка их в коллаж, по заданной стратегии.

Не держать сильную ссылку на ImageView. Грузить изображения не последовательно, а в несколько потоков. Корректно работать на ImageView в списках, на подобии ListView, RecycleView

## Задание 2

Запуск менее приоритетных задач на UI потоке, при наличии активной критической секции. Task.run() выполняется на UI- потоке

Пример - при скролле списка не сетить Bitmap'ы в ImageView

