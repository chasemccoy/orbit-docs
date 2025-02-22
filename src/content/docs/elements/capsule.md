---
title: capsule CSS Class
---

### CSS Class: `.capsule`

`Capsule` is a class to put text or another content. Currently, it can be used into `satellites` and `sides`.

### Customization

- **Alignment:** By default, `capsule` is placed at center of `satellite` or `side`. This behavior can be altered using alignment utility classes such as `.center-left`, `.center-right`, `.top-left`, `.top-center`, `.top-right`, `.bottom-left`, `.bottom-center`, and `.bottom-right`.

Besides that, to stablish `capsule` position following CSS classes can be set:
  - `stable`: to mantain content always horizontal. 
  - `turn-left`: to turn content 90deg left
  - `turn-right`: to turn content 90deg right
  - `flip`: to turn content upside-down.

- **Look and feel:** Capsules are initially invisible but can be customized by adding border and background properties.

### Usage

```html
<div class="satellite">
  <div class="capsule stable">
    Some text here.
  </div>
</div> 
```
