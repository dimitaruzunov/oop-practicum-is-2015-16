# Първо контролно по ООП практикум на втора група

## Задача 1. Концерт на група Фондацията

На 04.04.2016 се състоя концерта на група Фондацията със Симфоничния оркестър
на БНР в зала 1 на НДК. Билетите за концерта имат цени от 15 до 55 лева, като
има и ограничен брой специални билети, чиито притежатели получават
подарък от Фондацията (книга и диск с 14 песни, записани със
Симфоничния оркестър). Специалните билети имат цена 70 лева и
са само 30 броя - за първите 30 места в залата. Следната таблица
представя цените на билетите за съответните места:

| Места   | Цена в лева |
|---------|-------------|
| 1-30    | 70          |
| 31-70   | 55          |
| 71-100  | 30          |
| 101-150 | 15          |

Да се напише клас `Ticket`, който представя билет за концерта. Билетът
трябва да има две член-данни - място в залата и цена.
Конструкторът на `Ticket` да бъде само по зададено място в залата.
Цената на билета се определя на базата на мястото в залата чрез горната таблица.
Напишете "гетъри" за мястото и цената на билета. Напишете метод,
който извежда на стандартния изход информация за мястото и цената на билета.

Да се напише клас `Guest`, който представя фен на Фондацията, закупил билет
за концерта. Гостът трябва да има две член-данни - име (масив от символи) и билет.
Да се напише конструктор на `Guest` по име и билет.
Напишете метод, който проверява дали гостът получава подарък книга и диск.
Напишете метод, който извежда на стандартния изход
информация за госта - името и неговия билет.

Да се напише демонстрационна програма, която създава масив от петима гости
на концерта и извежда тези от тях, които получават подарък от Фондацията.
Извеждането да става чрез обхождане на създадения масив от гостите.

## Задача 2. Пицария

В една пицария клиентите могат да правят поръчки на пици.
Да се проектира съвкупност от класове с връзки между тях, които моделират
пицарията. За целта да се създадат следните класове:

- `Pizza` - пица с име и цена
- `Order` - поръчка, съдържаща списък от пици (списъкът да бъде представен
чрез масив)
- `Client` - клиент с име и поръчки (поръчките да бъдат представени чрез
масив)

Всеки клас трябва да има подходящ конструктор.

Да се реализират следните функционалности за класовете:

- добавяне на пица в поръчка
- намиране на общата сума на поръчка
- добавяне на поръчка за клиент
- намиране на цялата сума (за всички направени поръчки), която трябва да плати
клиента