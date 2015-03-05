## Named parameters

```sh
function foo({ from, to = 10 }) {
   ...
}

foo({ from: 1, to: 5 });
foo({ to: 5, from: 1 });
foo({ from: 1 });
```
<br>

<div>
```sh

function foo(positional, { named1, named2 }) {
   ...
}

foo(123, { named1: 'abc', named2: 'def' });
```
</div><!-- .element: class="fragment" data-fragment-index="1" -->
