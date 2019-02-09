# Film-Map-HTML-
HTML map with film locations in certain year

Модуль призначений для створення карти з локаціями фільмів певного року, якого обере користувач
і генерації цієї карти у вигляді HTML документа.

Необхідні модулі:

TQDM
Folium
Geopy

Модуль має два режими роботи, які користувач може обирати:

static - карта генерується швидше, але буде збережена тільки після повного виконання програми.

dynamic - карта генерується дещо повільніше, але користувач може спотерігати та перевіряти роботу,
відкривши документ у браузері та перезавантажуючи сторінку.

У модулі можна спостерігати за процесом виконання - буде представлення стрічка загрузки.


Створений HTML документ містить наступні теги:

!DOCTYPE html - Об'являє тип документа і представляє інформацію для браузера (мова і версія)
head - Елемент-контейнер для метаданих HTML-документа, таких як <title>, <meta>, <script>, <link>, <style>.
meta - Використовуєтья для збереження додаткової інформації про сторінку. Цю інформацію використовують браузери для оброблення сторінки, а пошукові системи — для її індексації.
script - Використовуєтья для опреділення сценарія на стороні клієнта (зазвичай JavaScript). Містить або текст скрипта, фбо вказує на зовнішній файл сценарія за допомогою атрибута src.
style - Підключає встроювані таблиці стилей.
body - Представляє тіло документа
div - Тег-контейнер для розділів HTML документа. Використовується для групування блочних елементів для форматування стилями.
 
 (Теги, зрозуміло мають бути написані так: <тег>, але це GitHub поле бачить це як реальний тег і тому відображається неправильно)
