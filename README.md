# Создание одностраничного сайта для проекта
# «Blanchard — художественная галерея».

Здравствуйте! Наша компания Blanchard занимается продажей предметов искусства. Мы не так
давно на рынке, и сейчас у нас возникла острая потребность в создании лендинга для нашей
художественной галереи. В целом, мы хотим продавать с этого сайта напрямую, однако сейчас
главная задача максимально быстро, сделать первую версию сайта с
возможностью подписки на все наши соцсети.

Нам нужен широкий охват пользователей и удобство сайта. Поэтому крайне важно, чтобы сайт
отображался с мобильных устройств, так как именно там большая часть нашей целевой
аудитории. Также хочется, чтобы сайт полностью совпадал с дизайн макетом, который
подготовил наш дизайнер. Помимо мобильных устройств, нам также важно охватить
пользователей десктоп версии нашего сайта. Другими словами, мы хотим, чтобы всё работало в
любом из современных браузеров.

# Функциональные требования

1. Лендинг должен иметь адаптивную вёрстку и корректно отображаться на компьютере,
планшете и мобильном устройстве: вся информация доступна и отображается.
2. Лендинг должен одинаково отображаться в браузерах Chrome, Firefox, Safari,
Opera, Edge.
3. В планшетной\мобильной версии: меню представляет собой кнопку, при нажатии на которую меню открывается и закрывается. Меню — на всю высоту экрана, при открытии сайт не должен скроллиться. Если высота сайта меньше высоты меню - меню должно скроллиться. Ссылка войти также переезжает в это меню.
4. В мобильной версии: все элементы центрируются.
5. В мобильной версии:
     *перелистывание слайдера должно работать по свайпу;
     *перелистывание меняется, вместо трех элементов листается по одному.

# Технологические требования
1. Чистая, адаптивная, семантическая вёрстка. Стремитесь минимизировать в коде количество тегов и вложенностей.
2. Пиксель-перфект вёрстка (под все разрешения). Возможны отличия на 1–3 пикселя.
3. В каждом из браузеров должна открываться абсолютно идентичная вёрстка. Кроссбраузерность
4. БЭМ-именование классов.
5. Минимум медиазапросов для реализации адаптива. Стремитесь использовать минимальное количество брейкпоинтов в вёрстке.
6. Избегайте дублирования кода для мобильной версии, насколько это
возможно. 
7. Различный функционал — слайдеры, плавный скролл по якорям, табы, аккордеоны и прочее — должен работать.
8. Использование SVG-иконок для создания иконок сайта.
9. Удобный юзабилити для пользователя; все кнопки и ссылки явно дают понять, что на них можно кликнуть (имеют ховер-эффект) и курсор-лапку, также отменён outline, но заменён на всех кликабельных элементах на псевдокласс :focus.
10. На мобильных устройствах ховеры не должны работать, вступает псевдокласс :active.
11. Флексбокс-вёрстка, без использования фреймворков.
12. Теги HTML- и CSS-документов должны быть валидными: проверка на https://validator.w3.org/ не должна выдавать ошибок и предупреждений.
