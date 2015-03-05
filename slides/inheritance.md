##  Inheritance

```sh
  class Employee extends Person {
    constructor(name, title) {
      super.constructor(name);
      this.title = title;
    }

    describe() {
      return super.describe() + " (" + this.title + ")";
    }
  }
```

<div>
```sh
  let yauheni = new Employee("Yauheni", "Developer");

  yauheni instanceof Person;
  yauheni instanceof Employee;
  yauheni.describe();
```
</div><!-- .element: class="fragment" data-fragment-index="1" -->

### <span class="red"> true</span> <!-- .element: class="red fragment" data-fragment-index="2" -->
### <span class="red"> true</span> <!-- .element: class="red fragment" data-fragment-index="3" -->
### <span class="red"> Person called Yauheni (Developer)</span> <!-- .element: class="red fragment" data-fragment-index="4" -->