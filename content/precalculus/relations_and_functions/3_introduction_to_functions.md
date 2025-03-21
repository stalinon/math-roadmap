---
title: "Введение в функции"
---

# Тема 3. Введение в функции

## 3.1 Определение функции

### Что такое функция?

**Функция** — это отношение, при котором каждому значению \( x \) соответствует ровно одно значение \( y \).

Формально:

{{< katex display=true >}}
f: X \to Y, \quad \text{где каждому } x \in X \text{ соответствует ровно одно } y \in Y.
{{< /katex >}}

Если отношение не соответствует этому правилу (например, одному \( x \) сопоставляются два \( y \)), то это **не функция**.

{{% hint info %}}
Функция — это как кофемашина: если ты выбираешь «латте», то всегда получаешь именно латте.  
Но если бы нажатие кнопки «латте» иногда давало капучино, то это не была бы функция!
{{% /hint %}}

### Примеры

1. **Функция**: \( f(x) = x^2 \), так как для каждого \( x \) есть только одно \( y \).
2. **Не функция**: \( x^2 + y^2 = 1 \) (окружность), так как для некоторых \( x \) существует два значения \( y \) (верхняя и нижняя часть окружности).

---

## 3.2 Графическое представление функций

Функцию можно изобразить графически на координатной плоскости.

### Вертикальный тест

Чтобы проверить, является ли график функцией, используют **вертикальный тест**:

- Если **любая вертикальная прямая** пересекает график **не более чем в одной точке**, это **функция**.
- Если вертикальная линия пересекает график в **двух и более точках**, это **не функция**.

{{% hint info %}}
Представь, что ты проводишь линейкой по экрану график.  
Если линейка пересекает его в двух точках одновременно — это не функция!
{{% /hint %}}

---

## 3.3 Область определения и множество значений

### Определения

- **Область определения (Domain)** — все возможные значения \( x \), для которых определена функция.
- **Множество значений (Range)** — все возможные \( y \), которые могут получиться.

Пример:

Для функции \( f(x) = x^2 \):

- **Область определения**: \( (-\infty, \infty) \) — можно подставить любое \( x \).
- **Множество значений**: \( [0, \infty) \) — потому что квадрат числа всегда неотрицателен.

{{% hint info %}}
Если функция — это торговый автомат, то  
**Область определения** — это кнопки, которые можно нажать,  
а **Множество значений** — это напитки, которые можно получить.
{{% /hint %}}

---

## 3.4 Способы задания функций

Функцию можно задать разными способами:

1. **Формулой** (алгебраически): \( f(x) = x^2 - 3x + 2 \).
2. **Таблицей значений**:  
   | \( x \) | -2 | -1 | 0 | 1 | 2 |
   |----|----|----|----|----|----|
   | \( y \) | 6 | 2 | 0 | 0 | 2 |
3. **Графиком** — путем нанесения точек на координатную плоскость.
4. **Словесным описанием**: «Функция берет число, умножает его на 3 и добавляет 5».

{{% hint info %}}
Формула — это как рецепт, таблица — как список покупок, а график — это уже готовое блюдо!
{{% /hint %}}

---

## 3.5 Основные типы функций

### Линейные функции

Формула:  
{{< katex display=true >}}
f(x) = mx + b
{{< /katex >}}

- \( m \) — угловой коэффициент (определяет наклон).
- \( b \) — точка пересечения с осью \( Y \).

Пример: \( f(x) = 2x + 3 \).

{{% hint info %}}
Если ты идешь с постоянной скоростью, то график пути будет линейной функцией.
{{% /hint %}}

### Квадратичные функции

Формула:  
{{< katex display=true >}}
f(x) = ax^2 + bx + c
{{< /katex >}}

- График — **парабола**.
- Если \( a > 0 \), парабола «улыбается» \( \smile \).
- Если \( a < 0 \), парабола «грустная» \( \frown \).

Пример: \( f(x) = x^2 - 4 \).

{{% hint info %}}
Если бросить мяч вверх, его траектория будет параболой!
{{% /hint %}}

---

## Итоги

1. **Функция** — это соответствие, где каждому \( x \) сопоставляется только одно \( y \).
2. **Вертикальный тест** помогает определить, является ли график функцией.
3. **Область определения** — возможные \( x \), **множество значений** — возможные \( y \).
4. **Функции можно задавать разными способами**: формулой, таблицей, графиком, словами.
5. **Основные типы функций**: линейные (прямая) и квадратичные (парабола).
