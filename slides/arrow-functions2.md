##  Arrow functions

```sh
  let baz = {
    foo: 13,
    bar() {
      setTimeout(() => {
        console.log(this.foo);
      }, 300);
    }
  }

  console.log(baz.bar());

```
<br>
<br>
# <span class="red"> 13 </span> <!-- .element: class="red fragment" data-fragment-index="1" -->