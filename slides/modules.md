##  Modules

### lib.js
```sh
  export const sqrt = Math.sqrt;
  export function square(x) {
    return x * x;
  }
  export function diag(x, y) {
    return sqrt(square(x) + square(y));
  }
```
<div>
### main.js
```sh
  import { square, diag } from 'lib';
  console.log(square(11));
  console.log(diag(4, 3));
```
</div><!-- .element: class="red fragment" data-fragment-index="1" -->
<br>

## <span class="red"> 121</span> <!-- .element: class="red fragment" data-fragment-index="2" -->

## <span class="red"> 5</span> <!-- .element: class="red fragment" data-fragment-index="3" -->