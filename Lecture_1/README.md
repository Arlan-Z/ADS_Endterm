# Complexity and Memory
## Константные операции

```python
var_a = 10
inf = float('inf')
print(inf)
```
>Вычислительная сложность -> O(1)


## Алгоритмы с линейной сложностью



```python
lst = [1, 2, 3, 4, 5, 8, 9, 15] # n элементов
for x in lst:
    print(x)
```
>Вычислительная сложность -> O(n)

## Алгоритмы с логарифмической сложностью и с факториальной сложностью
[Видео](https://www.youtube.com/watch?v=nVAPc2K8xpU&list=PLA0M1Bcd0w8x4jEp1r_aN3xlnlbfx9RQ2&index=2)
## Правила сложения и умножения

```python
for x in range(n):
    print(x)

for y in range(m):
    print(y)
```
>Вычислительная сложность -> O(n) + O(m) -> O(n + m)

---

```python
for x in range(n):
    for y in range(m):
        print(x, y)
```

>Вычислительная сложность -> O(n) * O(m) -> O(n * m)

## Порядок возрастания сложности алгоритмов
O(n!) > O(2 ^ n) > O(n ^ 2) > O(n logn) > O(n) > O(logn) > O(1)