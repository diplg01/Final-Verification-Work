# Итоговая проверочная работа
## Требования: 
* Создать репозиторий на GitHub;
* Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод);
* Снабдить репозиторий оформленным текстовым описанием решения(README.md);
* Написать программу, решающую поставленную задачу;
* Использовать контроль версий в работе над этим небольшим проектом (не должно быть так что всё залито одним коммитом)

---
## Задача:
Написать программу, которая из имеющегося
массива строк формирует массив строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

---
## Алгоритм выполнения:
1. Первоначальный массив textArray предложим пользователю ввести самостоятельно.
2. Для инициализации исходного массива необходимо указать его размер (length), который введет пользователь.
3. Выполним проверку введенных данных пользователем (должно быть натуральное число), и, в случае если они некорректны, попросим повторить ввод.
4. Используя цикл предложим заполнить массив строками.
5. Выведем в консоль полученный массив.
6. Размер (newLength) нового массива newTextArray узнаем подсчитав через цикл количество сторок, длина которых меньше либо равна 3 символа.
7. Заполним строками, длина которых меньше либо равна 3 символа, новый массив и выведем в консоль.