# Исследование свойства `justify-content` во Flexbox

📚 Этот репозиторий содержит материалы для изучения свойства `justify-content` в CSS Flexbox, включая интерактивную викторину, примеры кода и глоссарий терминов.

## 📌 Основная информация
Свойство `justify-content` управляет расположением элементов **вдоль главной оси** Flex-контейнера. Оно применяется к родительскому элементу с `display: flex`.

### Ключевые особенности:
- Зависит от направления оси (`flex-direction`)
- Работает только если есть свободное пространство
- Имеет 6 основных значений

## ✅ Интерактивная викторина
<details>
<summary>1. К какому элементу применяется свойство justify-content?</summary>

**Ответ:** К родительскому Flex-контейнеру.
</details>

<details>
<summary>2. Что определяет justify-content?</summary>

**Ответ:** Распределение элементов вдоль главной оси.
</details>

<details>
<summary>3. Как flex-direction влияет на justify-content?</summary>

**Ответ:** Определяет направление главной оси (row/column).
</details>

<details>
<summary>4. Значение по умолчанию для row?</summary>

**Ответ:** `flex-start` (элементы у начала оси).
</details>

<details>
<summary>5. Что делает flex-end?</summary>

**Ответ:** Смещает элементы к концу оси.
</details>

<details>
<summary>6. Как центрировать элементы?</summary>

**Ответ:** Использовать `justify-content: center`.
</details>

<details>
<summary>7. Разница space-between и space-around?</summary>

**Ответ:**  
- `space-between` = равные промежутки между  
- `space-around` = равные отступы вокруг
</details>

<details>
<summary>8. Какое значение делает все промежутки равными?</summary>

**Ответ:** `space-evenly`.
</details>

<details>
<summary>9. Когда главная ось вертикальна?</summary>

**Ответ:** При `flex-direction: column`.
</details>

<details>
<summary>10. Почему важны эксперименты?</summary>

**Ответ:** Позволяют понять поведение в разных сценариях.
</details>

## 📖 Глоссарий
| Термин | Описание |
|--------|-----------|
| Flexbox | Модуль CSS для гибкого расположения элементов |
| Главная ось | Основная ось размещения |
| `space-between` | Равные промежутки между элементами |
| `space-evenly` | Равные промежутки везде |
| `flex-start` | Значение по умолчанию |

## 💡 Вопросы для эссе
1. Взаимодействие `flex-direction` и `justify-content`
2. Сравнение `space-*` значений
3. Важность значения `flex-start`
4. Адаптивный дизайн с `justify-content`
5. Расширенные значения свойства

## 🚀 Примеры кода
Смотрите файл [index.html](index.html) с полными примерами всех значений.