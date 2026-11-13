# Данные велосети «Нейровектор»

Учебное задание, сайт и данные подготовлены при поддержке Авито. Мир «Альтернативное будущее», города, сеть магазинов и объявления вымышлены.

По 300 объявлений каждого города за 2023–2025 годы:

- [ИИград](iigrad/bicycles.json)
- [Аналитиск](analitisk/bicycles.json)
- [Даталесье](datalesye/bicycles.json)

[cities.json](cities.json) содержит названия городов, пути и количество записей. Каждый файл объявлений возвращает JSON-массив. Легенда, описание полей и задания находятся в [index.html](index.html).

## GitHub Pages

В Settings → Pages выберите Deploy from a branch, ветку main и папку /(root).

Адрес сайта после публикации: https://yupest.github.io/avito-bicycle-demo/.

Пример GET: https://yupest.github.io/avito-bicycle-demo/iigrad/bicycles.json.

Генератор данных остается локальным и исключен через .gitignore. Набор представляет учебную модель API.
