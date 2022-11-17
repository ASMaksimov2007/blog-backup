---
layout: single
title: Теорминимум по теорверу
permalink: /teorver/
---

# Логика высказываний

### Кванторы
$\forall$ - любой/для каждого - все

$\exists$ - существует - некоторые

### Отрицания

Все кролики белые = любой кролик белый

**Отрицание**: Существует НЕ белый кролик

Есть белый кролик = Существует белый кролик

**Отрицание**: ВСЕ кролики не белые

Обратите внимание: при отрицании И меняется на ИЛИ и наоборот. Квантор тоже меняется.

##### Задание

Постройте отрицания:
1. На Марсе есть жизнь
2. Все птицы летают
3. Не каждая птица долетит до середины Днепра
4. Некоторые школьники едят бутерброды во время перерыва
5. Стены школы желтые и зеленые
6. Кролик белый и пушистый
7. Любой шестиклассник выше Эйфелевой башни

# Множества

Множество состоит из элементов: $x \in A$, где $x$ - элемент, $A$ - множество.

### Способы задать множество

1. Перечисление: $\mathbb{N} = \\{1, 2, 3, ...\\}$, $\mathbb{Z} = \\{..., -1, 0, 1, 2, ...\\}$, $\varnothing = \\{\\}$
2. Характеристика: $\mathbb{Q} = \\{\frac{p}{q} \mid p \in \mathbb{Z}, q \in \mathbb{N}\\}$

$\mathbb{A}$ является _подмножеством_ $\mathbb{B} \Leftrightarrow x \in \mathbb{A} \Rightarrow x \in \mathbb{B}$, то есть каждый элемент $\mathbb{A}$ является элементом $\mathbb{B}$. Это записывается как $\mathbb{A} \subset \mathbb{B}$.

Из этого следует, что если $\mathbb{A} = \mathbb{B}$, то $\mathbb{A} \subset \mathbb{B}$ и $\mathbb{A} \supset \mathbb{B}$.

Пустое множество является подмножеством любого множества.

##### Задание

1. Задайте множество чисел, кратных $14$.
2. Какой из знаков нужно поставить вместо $\wedge$?
    - $1 \wedge \mathbb{N}$
    - $\\{1\\} \wedge \mathbb{N}$
    - $\mathbb{A} \wedge \mathbb{A}$
    - $\mathbb{A} \wedge \\{\mathbb{A}\\}$
    - $\varnothing \wedge \mathbb{A}$
    - $\varnothing \wedge \\{\mathbb{A}, \mathbb{B}\\}$

### Операции над множествами

- Объединение: $\mathbb{A} \cup \mathbb{B} = \\{x \mid x \in \mathbb{A}$ или $x \in \mathbb{B}\\}$
- Пересечение: $\mathbb{A} \cap \mathbb{B} = \\{x \mid x \in \mathbb{A}$ и $x \in \mathbb{B}\\}$
- Разность: $\mathbb{A} \backslash \mathbb{B} = \\{x \mid x \in \mathbb{A}$ и $x \notin \mathbb{B}\\}$
- Симметрическая разность: $\mathbb{A} \bigtriangleup \mathbb{B} = (\mathbb{A} \backslash \mathbb{B}) \cup (\mathbb{B} \backslash \mathbb{A})$
- Декартово произведение: $\mathbb{A} \times \mathbb{B} = \\{(x, y) \mid x \in \mathbb{A}, y \in \mathbb{B}\\}$
- Множество всех подмножеств: $2^{\mathbb{A}} = \\{\mathbb{B} \mid \mathbb{B} \subset \mathbb{A}\\}$
