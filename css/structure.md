# 枠組み部分
## ブロック

木構造の上の方に位置するタグにつけるクラス名

構造的に大きい部分: header, ul, など

|Name         |Tags       |
|----         |----       |
|.header      |header>div |
|.footer      |footer>div |
|.main        |div        |
|.container   |div        |
|.menu        |ul         |
|.box         |div

## 要素

ブロック内のタグに付けるクラス

.menu-item のように ブロック-要素 の形とする

|Name  |Tags   |Example
|---   |---    |---
|title |h1     |.header-title
|item  |li     |.menu-item
|link  |a      |.hoge-link

## 状態

ブロックの状態を表すクラス

.is-active のように is-状態 の形とする

|Name   |Tags |Example
|---    |---  |---
|active |*    |.is-active
|hover  |*    |.is-hover
