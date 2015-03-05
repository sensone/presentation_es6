### Let

```sh
  let first = 'Yauheni';
  let last = 'Korsunau';

  let obj = {
    first: first,
    last: last
  };

```
<div>
### compact
```sh
  let obj = { first, last };

```
</div><!-- .element: class="fragment" data-fragment-index="1" -->
<br>
<div>
```sh
  let propKey = 'hello';
  let obj = {
    [propkey]() {
      return 'hi';
    }
  };
  console.log(obj.hello());

```
</div><!-- .element: class="fragment" data-fragment-index="2" -->

## <span class="red"> hi</span> <!-- .element: class="red fragment" data-fragment-index="3" -->