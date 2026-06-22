# Шаг 12. Форма: чекбоксы

[Оглавление](00-karta-kursa.md) | [Назад: Шаг 11](11-forma-radioknopki.md) | [Дальше: Шаг 13](13-css-zachem-oformlenie.md)

## Цель

Добавить выбор нескольких вариантов.

## Новый прием

`type="checkbox"` создает чекбокс.

Чекбоксы нужны, когда можно выбрать несколько вариантов сразу.

## Что добавить

Внутрь формы после радиокнопок добавь:

```html
<p>Что добавить на сайт?</p>

<label>
  <input type="checkbox" name="add_picture" value="yes">
  Больше картинок
</label>

<label>
  <input type="checkbox" name="add_quiz" value="yes">
  Мини-викторину
</label>

<label>
  <input type="checkbox" name="add_jokes" value="yes">
  Веселые вопросы
</label>
```

## Что должно получиться внутри формы

Сначала попробуй сделать сам. Открывай этот блок, если стало трудно.

<details>
<summary>Подсмотреть готовый вариант</summary>

```html
<form>
  <label for="idea">О чем сделать факт?</label>
  <input id="idea" name="idea" type="text">

  <p>Какая тема тебе интереснее всего?</p>

  <label>
    <input type="radio" name="topic" value="space">
    Космос
  </label>

  <label>
    <input type="radio" name="topic" value="nature">
    Природа
  </label>

  <label>
    <input type="radio" name="topic" value="inventions">
    Изобретения
  </label>

  <label>
    <input type="radio" name="topic" value="person">
    Человек
  </label>

  <p>Что добавить на сайт?</p>

  <label>
    <input type="checkbox" name="add_picture" value="yes">
    Больше картинок
  </label>

  <label>
    <input type="checkbox" name="add_quiz" value="yes">
    Мини-викторину
  </label>

  <label>
    <input type="checkbox" name="add_jokes" value="yes">
    Веселые вопросы
  </label>
</form>
```

</details>

## Проверка

Попробуй выбрать несколько чекбоксов сразу.

В отличие от радиокнопок, чекбоксов может быть выбрано несколько.

## Маленькое задание

Добавь кнопку в конец формы:

```html
<button type="button">Готово</button>
```

Кнопка пока ничего не отправляет. Она просто показывает, как может выглядеть конец формы.

---

[Оглавление](00-karta-kursa.md) | [Назад: Шаг 11](11-forma-radioknopki.md) | [Дальше: Шаг 13](13-css-zachem-oformlenie.md)
