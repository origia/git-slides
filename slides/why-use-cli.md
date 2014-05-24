## それって便利？

* 慣れるとGUIより速い
* 自動化しやすい

<h3 class="fragment" data-fragment-index="1">例えば</h3>

1. Dropboxに入ってる画像を別のところに動かす <!-- .element: class="fragment" data-fragment-index="1" -->
2. すべての画像を800x600に変える <!-- .element: class="fragment" data-fragment-index="1" -->
3. 1日1回やりたい <!-- .element: class="fragment" data-fragment-index="1" -->

```
find ~/Dropbox -iname "*.jpg" -o -iname "*.png" | xargs -I{} mv {} .
mogrify -resize 800x600 *
```
<!-- .element: class="fragment" data-fragment-index="2" -->

ファイルに保存して, あと自動化するために1行書くだけ！<!-- .element: class="fragment" data-fragment-index="2" -->
