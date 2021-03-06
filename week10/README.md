# Упражнение 10

## Задача 1. Стек

Стекът е структура от данни, която представлява колекция от елементи с две
основни операции: `push`, която добавя елемент в края на колекцията
(края на колекцията ще наричаме връх на стека), и `pop`, която премахва последно
добавения елемент (тоест премахва елемента на върха на стека).

Да се имплементира структурата от данни стек от елементи от произволен тип.
Да бъде реализирано свързано представяне на стека.

За целта да се напише шаблон на клас `Stack`, който да има следните член-данни:

- `Т* top` - указател към върха на стека
- `int size` - брой елементи в стека

Напишете конструктор по подразбиране за класа `Stack`, който
инициализара празен стек.

Реализирайте следните публични методи на класа `Stack`:

- `int getSize() const;` - връща броя елементи в стека
- `bool isEmpty() const;` - проверява дали стека е празен
- `const T& getTop() const;` - връща елемента на върха на стека
- `void push(T element);` - добавяне на елемент в стека
- `void pop();` - премахване на елемент от стека

Да се напише "голяма четворка" за класа `Stack`.

# Задача 2. Студенти и работници

Дефинирайте клас `Person`, притежаващ име, фамилия и години. Да се напише
метод `print` на `Person`, извеждащ информация за човека.

Дефинирайте клас `Student`, наследяващ `Person`, който представя студент
и има член-данни специалност и оценка. Да се напише метод `print` на
`Student`, извеждащ информация за студента.

Дефинирайте клас `Worker`, наследяващ `Person`, който представя работник
и има член-данни парите, които получава работникът за 1 час работа,
и общ брой изработени часове. Да се напише метод `print`,
извеждащ информация за работника. Да се напише метод `calculateSalary`,
пресмятащ заплатата на работника, която получава за броя
изработени от него часове.
