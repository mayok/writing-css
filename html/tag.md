# html の書き方

## タグ
html5 で登場した section, article, nav, aside, などは使わない

基本的にクラスで解決する

なぜ: タグ名で悩まないようにするため

例外: header, main, footer は使用する. まとまりを囲むだけで css で装飾はしない

```
<header>
  <div class="header">
    <h1>Header 1</h1>
  </div>
</header>

<main>
  <div class="main">
    <div class="container">
      {{ content  }}
    </div>
  </div>
</main>

<footer>
  <div class="footer">
    <ul>
      <li></li>
      <li></li>
      <li></li>
    </ul>
  </div>
</footer>
```
