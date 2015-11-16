# javascript との連携する際の注意点

javascript から css をいじる場合 js- をつけたクラスを追加する

ただし、js- は css ファイル内に存在してはならない (css では使わない)

```html
<ul class="menu js-menu">
  <li class="menu-item"></li>
  <li class="menu-item"></li>
  <li class="menu-item"></li>
</ul>
```

```css
.menu {
  &-item {
  }
}
```

```js
var menu = document.querySelector('.js-menu');
```
