##  For -of

```sh
  let arr = [ "blue", "green" ];
  arr.notAnIndex = 123;
  Array.prototype.protoProp = 456;

  for (let x in arr) {
     console.log(x);
  }
```
<br>
### <span class="red">blue, green, notAnIndex, protoProp <!-- .element: class="red fragment" data-fragment-index="1" -->
<br>
<div>
```sh
  for (let x of arr) {
    console.log(x);
  }
```
</div><!-- .element: class="fragment" data-fragment-index="2" -->
<br>
### <span class="red">blue, green<!-- .element: class="red fragment" data-fragment-index="3" -->