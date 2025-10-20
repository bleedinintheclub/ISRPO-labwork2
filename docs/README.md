<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=306998&width=435&lines=Лабораторная+работа+2" alt="lab header" />
</div>

<p>
  <img src="https://www.python.org/static/community_logos/python-logo.png"
       alt="Python logo" width="200">
</p>

<p>
  🔗 <a href="https://docs.python.org/3/" target="_blank">Официальная документация Python</a>
</p>

# Math formulas
## Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²

## Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a

---

## Общее описание
Проект предназначен для вычисления **площади** и **периметра** основных геометрических фигур.
Реализован на языке **Python**.

---

## Структура проекта
- **circle.py** — функции для круга
- **square.py** — функции для квадрата
- **docs/** — документация проекта

---

# Библиотека `geometric_lib`

Набор функций для выполнения базовых геометрических вычислений.

---

## 1. Круг (`circle.py`)

### `circle_area(r: float) -> float`
Вычисляет площадь круга по радиусу.

**Параметры:**
- `r` (`float`) — радиус круга.

**Возвращает:**
- `float` — площадь круга.

**Пример:**
```python
>>> circle_area(5)
78.53981633974483
```

### `circle_perimeter(r: float) -> float`
Вычисляет длину окружности по радиусу.

**Параметры:**
- `r` (`float`) — радиус круга.

**Возвращает:**
- `float` — длина окружности.

**Пример:**
```python
>>> circle_perimeter(5)
31.41592653589793
```

---

## 2. Квадрат (`square.py`)

### `square_area(a: float) -> float`
Вычисляет площадь квадрата по длине стороны.

**Параметры:**
- `a` (`float`) — длина стороны квадрата.

**Возвращает:**
- `float` — площадь квадрата.

**Пример:**
```python
>>> square_area(5)
25
```

### `square_perimeter(a: float) -> float`
Вычисляет периметр квадрата по длине стороны.

**Параметры:**
- `a` (`float`) — длина стороны квадрата.

**Возвращает:**
- `float` — периметр квадрата.

**Пример:**
```python
>>> square_perimeter(5)
20
```

---

## История изменений

- f516dae Add function documentation and examples in docstrings
- d078c8d L-03: Docs added
- 8ba9aeb L-03: Circle and square added

