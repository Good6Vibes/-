# Баг-репорты
##### Баг-репорт №1

| Заголовок | На странице входа кнопка «Войти» имеет не тот размер и надпись |
| ------ | ------ |
| Описание | На странице входа кнопка «Сохранить изменения» должна называться «Войти» и быть меньше по ширине |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] |
| Текущий результат | ![1](1.png) |
| Ожидаемый результат | ![1](2.png) |
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18 |
| Критичность | Незначительный |

##### Баг-репорт №2

| Заголовок | На странице входа отсутствует хедер сайта  |
| ------ | ------ |
| Описание | На странице входа отсутствует хедер сайта с LOGO и иконкой шестеренки (настройки) |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] |
| Текущий результат | ![1](3.png) |
| Ожидаемый результат | ![1](4.png) |
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18  |
| Критичность | Незначительный |

##### Баг-репорт №3

| Заголовок |В хедере надпись LOGO не того размера на всех страницах  |
| ------ | ------ |
| Описание | В хедере надпись LOGO не того размера, что в макете. В макете надпись по размеру меньше |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать кнопку «Сохранить изменения»|
| Текущий результат | ![1](5.png) |
| Ожидаемый результат | ![1](6.png) |
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18  |
| Критичность | Тривиальный |

##### Баг-репорт №4

| Заголовок | На странице главного меню заголовок «Активные сертификаты» выровнен не по центру  |
| ------ | ------ |
| Описание | На странице главного меню заголовок «Активные сертификаты» выровнен не по центру, а по левому краю |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать кнопку «Сохранить изменения»|
| Текущий результат | ![1](7.png) |
| Ожидаемый результат | ![1](8.png) |
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18  |
| Критичность | Тривиальный |

##### Баг-репорт №5

| Заголовок | На странице главного меню иконка добавления сертификата отличается от иконки в макете  |
| ------ | ------ |
| Описание | На странице главного меню иконка добавления сертификата отличается от иконки в макете |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать кнопку «Сохранить изменения»|
| Текущий результат | ![1](9.png) |
| Ожидаемый результат | ![1](10.png) |
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18  |
| Критичность | Тривиальный |

##### Баг-репорт №6

| Заголовок | На странице редактирования сертификата плейсхолдеры не соответствуют полям ввода   |
| ------ | ------ |
| Описание | На странице редактирования сертификата у трех полей ввода неправильные плейсхолдеры: стоимость, описание и возрастная категория |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать кнопку «Сохранить изменения» <br> 3. Нажать на иконку «карандаш» на сертификате|
| Текущий результат | ![1](11.png) |
| Ожидаемый результат | Каждому полю ввода соответствует свой плейсхолдер:<br>Стоимость-Стоимость сертификата <br> Описание-Описание сертификата <br> Возрастная категория-Возрастная категория сертификата|
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18 |
| Критичность | Тривиальный |

##### Баг-репорт №8

| Заголовок | На странице редактирования сертификата кнопка «Сохранить изменения» не соответствует размеру |
| ------ | ------ |
| Описание | кнопка «Сохранить изменения» шире, чем в макете |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать кнопку «Сохранить изменения» <br> 3. Нажать на иконку «карандаш» на сертификате|
| Текущий результат | ![1](12.png) |
| Ожидаемый результат | ![1](13.png) |
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18 |
| Критичность | Тривиальный |

##### Баг-репорт №9

| Заголовок | В модальном окне удаления сертификата кнопка «Нет, не удалять» имеет лишний желтый фон |
| ------ | ------ |
| Описание | В модальном окне удаления сертификата кнопка «Нет, не удалять» имеет лишний желтый фон, текст сливается с фоном и не читается |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать кнопку «Сохранить изменения» <br> 3. Нажать на красный крестик на сертификате|
| Текущий результат | ![1](14.png) |
| Ожидаемый результат | ![1](15.png) |
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18 |
| Критичность | Значительный |

##### Баг-репорт №10

| Заголовок | На странице редактирования пользователя поле ввода Telegram ID не кликабельно  |
| ------ | ------ |
| Описание | В поле ввода Telegram ID не возможно ввести значение |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать кнопку «Сохранить изменения» <br> 3. Нажать на «Пользователи» на боковой панели <br> 4. Нажать на иконку карандаша напротив почты пользователя |
| Текущий результат | ![1](16.png) |
| Ожидаемый результат | ![1](17.png) |
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18 |
| Критичность | Значительный |

##### Баг-репорт №11

| Заголовок | На странице добавления сертификата плейсхолдеры не соответствуют полям ввода  |
| ------ | ------ |
| Описание | На странице добавления сертификата у трех полей ввода неправильные плейсхолдеры: стоимость, описание и возрастная категория  |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать кнопку «Сохранить изменения» <br> 3. Нажать на кнопку добавления сертификата |
| Текущий результат | ![1](18.png) |
| Ожидаемый результат | Каждому полю ввода соответствует свой плейсхолдер:<br>Стоимость-Стоимость сертификата <br> Описание-Описание сертификата <br> Возрастная категория-Возрастная категория сертификата |
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18 |
| Критичность | Значительный |

##### Баг-репорт №12

| Заголовок | На странице добавления сертификата кнопка «Добавить» не той ширины  |
| ------ | ------ |
| Описание | На странице добавления сертификата кнопка «Добавить» шире, чем в макете  |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать кнопку «Сохранить изменения» <br> 3. Нажать на кнопку добавления сертификата |
| Текущий результат | ![1](19.png) |
| Ожидаемый результат | ![1](20.png) |
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18 |
| Критичность | Тривиальный |

##### Баг-репорт №13

| Заголовок | На странице реферальной системы в поле Вознаграждение отсутствует обозначение валюты рубля  |
| ------ | ------ |
| Описание | В поле Вознаграждение отсутствует обозначение валюты рубля  |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать кнопку «Сохранить изменения» <br> 3. Нажать на «Реферальная система» на боковой панели |
| Текущий результат | ![1](21.png) |
| Ожидаемый результат | ![1](22.png) |
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18 |
| Критичность | Тривиальный |

##### Баг-репорт №14

| Заголовок | На странице редактирования пользователя в полях ввода некликабельная иконка редактирования  |
| ------ | ------ |
| Описание | При нажатии на иконку редактирования ![1](25.png) ничего не происходит  |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать кнопку «Сохранить изменения» <br> 3. Нажать на «Пользователи» на боковой панели <br> 4. Нажать на иконку карандаша напротив почты пользователя |
| Текущий результат | При нажатии на иконку редктирования ничего не происходит |
| Ожидаемый результат | При нажатии на иконку редктирования данные в полях ввода редактируются и сохраняются |
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18 |
| Критичность | Значительный |

##### Баг-репорт №15

| Заголовок | На странице ввода промокода кнопка «Активировать» не того размера  |
| ------ | ------ |
| Описание | Кнопка «Активировать» по размеру шире, чем в макете  |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать кнопку «Сохранить изменения» <br> 3. Нажать на кнопку добавления промокода |
| Текущий результат | ![1](23.png) |
| Ожидаемый результат | ![1](24.png) |
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18 |
| Критичность | Значительный |

##### Баг-репорт №16

| Заголовок | На странице главного меню в хедере значок настроек не кликабельный  |
| ------ | ------ |
| Описание | На странице главного меню в хедере значок настроек ![1](26.png) не кликабельный  |
| Шаги воспроизведения |  1. Перейти по ссылке [http://ujvm-ot9.turtlesource.tech/] <br> 2. Нажать кнопку «Сохранить изменения» |
| Текущий результат | При нажатии на иконку настроек, иконка не реагирует  |
| Ожидаемый результат | Иконка настроек кликабельна |
| Тестовое окружение | Google Chrome version 129.0.6668.101 <br> Mozilla Firefox version 131.0.3 <br> Yandex version 24.7.6.974 <br> Safari 18 |
| Критичность | Значительный |
