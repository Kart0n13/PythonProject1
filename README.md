# PythonProject1
Этот скрипт на Python генерирует пары целых чисел в двух различных порядках на основе введённого неотрицательного целого числа 𝑛. 
Включает функции для создания пар в прямом и обратном порядке.

Функции
direct_pairs(n)
Вход: Неотрицательное целое число 𝑛
Выход: Список кортежей, содержащих все возможные пары 
(𝑖,𝑗)
(i,j), 
где 
0 ≤ 𝑖
𝑗 ≤ 𝑛
0 ≤ i , j ≤ n.
Описание: Эта функция использует вложенные циклы для генерации пар в возрастающем порядке, начиная с (0, 0) и заканчивая (n, n).
reverse_pairs(n)
Вход: Неотрицательное целое число 𝑛.
Выход: Список кортежей, содержащих все возможные пары 
(𝑖 , 𝑗)
(i,j) в обратном порядке.
Описание: Эта функция вызывает direct_pairs(n) для генерации пар и затем разворачивает список, чтобы вывести пары от (n, n) до (0, 0).
