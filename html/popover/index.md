---
title: "Popover API"
description: "Нативный способ создавать всплывающие элементы."
authors:
  - solarrust
related:
  - html/dialog
  - html/button
  - a11y/role-tooltip
tags:
  - doka
---

## Кратко

Удобный способ создавать всплываютщие элементы. Новая возможность HTML. Имеет много встроенных фишек типа закрытия по клику мимо элемента или по нажатию кнопки <kbd>Esc</kbd>.

Можно управлять как при помощи атрибутов HTML, так и через JavaScript.

## Пример

```html
<button
  popovertarget="my-popover"
  popovertargetaction="toggle"
>
  Всплываем!
</button>

<div id="my-popover" popover>
    <p>🛳️</p>
</div>
```
