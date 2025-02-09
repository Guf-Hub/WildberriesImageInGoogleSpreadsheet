# Добавление главных изображений карточек товаров с сайта Wildberries в Google таблицу
<!-- HEADER START -->
<p style='text-align: center;'>
  <a href="https://openapi.wb.ru/"><img src="https://github.com/Guf-Hub/wbImageInSpreadsheet/assets/72359732/8f67c22c-97d1-4e9a-ae07-1fa94251eb56"></a>
</p>
<hr />
<!-- HEADER END -->

Получение изображений в Google таблицу по коду товара (nmId) Wildberries.</br>

[![Donate](https://img.shields.io/badge/Donate-Yoomoney-green.svg)](https://yoomoney.ru/to/410019620244262)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/Guf-Hub/WildberriesImageInGoogleSpreadsheet)
![javascript](https://img.shields.io/badge/lang-javascript-red)
![GAS](https://img.shields.io/badge/google-apps%20script-red)

[**Пример таблицы**](https://docs.google.com/spreadsheets/d/1XS6EjLATRreuuVR9YyISTQfkWPNAbYGhW_GW_m2ylec/edit#gid=0)<br/>
[**Feedback**](https://t.me/nosaev_m)<br/>

## Использование:
* Полностью копируйте [скрипт](https://github.com/Guf-Hub/wbPhotoLink/blob/main/Code.js) в свою таблицу;
* Заполните столбец кодами `nmId`;
* Укажите свои данные в `CONFIG`:
```JavaScript
const CONFIG = {
  sheetName: "Товары", // название листа книги для вставки
  wbIdColumn: 1, // номер столбца, по порядку, с nmId Wildberries (формат столбца должен быть число)
  pastColumn: 2, // номер столбца, по порядку, для вставки ссылок на изображения
};
```
* Сохраните изменения;
* Запустите скрипт > `🔽 Меню`;
* [Пройдите авторизацию](https://dzen.ru/media/excelifehack/kak-avtorizovat-skript-v-google-tablicah-61a943694333203e458eb600).

## Где найти `nmId`?
В отчетах личного кабинета или в ссылке на товара на сайте Wildberries: 
![image](https://user-images.githubusercontent.com/72359732/226750045-8e2054cd-4b7a-4f7c-8442-be08097e0d2e.png)


## Copyright & License

[MIT License](LICENSE)

Copyright (©) 2022 by [Mikhail Nosaev](https://github.com/Guf-Hub)
