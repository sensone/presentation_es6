##  Arrow functions

<div class="left">
  <span class="red">Аrrow functions </span> — это синтаксический сахар над существующими анонимными функциями
  <br>
  <br>

  <div>Нельзя использовать arrow-функции как конструкторы (<span class="red">new (() => {})</span>)</div><!-- .element: class="fragment" data-fragment-index="1" -->
  <br>
  <br>
  <div>Arrow-функции не могут обратиться к переменной <span class="red">arguments</span></div><!-- .element: class="fragment" data-fragment-index="2" -->
</div>
<br>
<div>
```sh
  let arr = [1, 2, 3];
  let squares = arr.map(x => x * x);
```
</div><!-- .element: class="fragment" data-fragment-index="3" -->
<br>
## <span class="red"> [1, 4, 9]</span> <!-- .element: class="red fragment" data-fragment-index="4" -->
