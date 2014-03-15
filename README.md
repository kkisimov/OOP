##Упражнение4 - Работа с динамична памет. Канонично представяне

###Задача1.

Да се дефинира клас ```Label```, който представлява етикет на продукт в магазин. Етикетът се характеризира с:

*Баркод
*Съдържание

За класа да се дефинират конструктори(по подразбиране, за общо ползване, за копиране), оператор за присвояване, деструктор, set и get функции. Да се дефинира функция, която стравнява два етикета, като по-голям е този етикет, чието съдържание е по-дълго.

###Задача2.

Да се дефинира клас ```Product```, който представлява продукт в магазин. Продуктът се характеризира с:

*Име
*Срок на годност
*Тегло(в грамове)
*Цена
*Етикет(```Label```)

За класа да се дефинират конструктори(по подразбиране, за общо ползване, за копиране), оператор за присвояване, деструктор, set и get функции.
Да се дефинират функции, които сравняват два продукта по цена и по тегло. 

###Задача3. 

Да се дефинира клас ```Shopper```, който представлява клиент в магазин. Клиентът се характеризира с:

*Продукти, които пазарува
*Пари в брой

За класа да се дефинират конструктори(по подразбиране, за общо ползване, за копиране), оператор за присвояване, деструктор, set и get функции. 
Да се дефинира функция, която:
*намира общото тегно на всички продукти, взети от клиента
*намира общата сума на всички продукти, взети от клиента
*проверява, дали има достатъчно пари в брой, за да плати за взетите продукти
*извършва плащане на закупените продукти, ако това е възможно
*добавя нов продукт
*премахва продукт по зададено име(ако има два продукта с еднакво име да се премахва първият по реда на проверяването)
