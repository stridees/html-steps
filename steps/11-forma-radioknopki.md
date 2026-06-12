# Шаг 11. Форма: радиокнопки

[Оглавление](00-karta-kursa.md) | [Назад: Шаг 10](10-forma-pole-vvoda.md) | [Дальше: Шаг 12](12-forma-chekboksy.md)

## Цель

Добавить выбор одной любимой темы.

## Новый прием

`type="radio"` создает радиокнопку.

Радиокнопки нужны, когда можно выбрать только один вариант.

Чтобы варианты работали как одна группа, у них должен быть одинаковый `name`.

## Что добавить

Внутрь формы после поля ввода добавь:

```html
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
</form>
```

</details>

## Проверка

Попробуй нажать на разные радиокнопки.

Выбранной остается только одна.

## Маленькое задание

Добавь четвертую радиокнопку:

```html
<label>
  <input type="radio" name="topic" value="person">
  Человек
</label>
```

---

[Оглавление](00-karta-kursa.md) | [Назад: Шаг 10](10-forma-pole-vvoda.md) | [Дальше: Шаг 12](12-forma-chekboksy.md)
