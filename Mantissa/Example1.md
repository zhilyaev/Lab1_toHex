# Пример X = 36
X = 36<sub>10</sub> = 24<sub>16</sub> = 0010 0100<sub>2</sub>

- Сейчас запятая стоит вот так: 00100100 **.** 
- Надо вот так: 00 **.** 100100  
### Порядок
| 0 | 0 | 1 | 0 | 0 | 1 | 0 | 0 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| - | - | **6** | 5 | 4 | 3 | 2 | 1 |
> Смещаем запятую, до первой едницы.

- Порядок = **6**<sub>10</sub> = 0000 0**110**<sub>2</sub> 
- Прибавляем единицу, в старший разряд порядка = **1**000 0110
### Нормализация Мантиссы
X = 36<sub>10</sub> = 24<sub>16</sub> = 0010 0100<sub>2</sub> 

> Мантисса сейчас = 100100. 
Но так как мы смещаем всегда до первой единицы. То она там **всегда**. Следовательно, зачем нам тратить лишний бит?
_Первую единцу НЕ ЗАПИСЫВАЕМ_

Мантисса = 00100

### Итог

| Знаковый 1 бит  | Порядок 8 бит | Мантисса 23 бита |
|:---------------:|:----------:|:--------:|
|0| 1000 0110 | 001 0000 0000 0000 0000 0000|

0100 0011 0001 0000 0000 0000 0000 0000<sub>2</sub> = 4310 0000<sub>16</sub>