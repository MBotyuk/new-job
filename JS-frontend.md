Необходимо создать витрину для интернет-магазина.

В этой витрине можно походить по категориям, зайти в любую категорию, посмотреть на товары в этой категории. Если кликнуть на товар - открывается страница с детальным описанием товара.

Товары можно класть в корзину. На любой странице есть ссылка, открывающая корзину. В корзине можно посмотреть все товары, добавленные туда раньше. Пример можно посмотреть тут: https://mdemo.ecwid.com/simple-store


Примерный список "виртуальных" страниц:
- Список категорий с товарами. Отображается список категорий и товаров в этой категории. Если ткнуть на категорию - мы переходим в эту категорию и видим все подкатегории и товары в выбранной категории
- При клике на товар - открывается страница с его детальным описанием, крупной картинкой etc
- При клике на ссылку корзины - открывается корзина, в ней можно посмотреть все товары что были туда добавлены, а так же общая сумма набранных товаров.

Как делать:
- Создать аккаунт на mydev.ecwid.com
- Сделать этот аккаунт платным, чтобы были доступно API (вводить тестовую кредитку, номера есть в интернете)
- Ознакомится с документацией по Ecwid Product API тут - http://kb.ecwid.com/w/page/25285101/Product%20API
(все ссылки вида app.ecwid.com надо заменять на appdev.ecwid.com)
- Это должна быть одна HTML страница, которая содержит несколько "виртуальных" страниц, полностью создаваемых через Javascript.
- Данные необходимо получать с нашего сервера используя JSONP
- Можно использовать любые (!) Javascript/CSS библиотеки. Можно вообще ничего не использовать и фигачить на чистом JS/CSS.
- По всем вопросам смело писать на vgv@ecwid.com