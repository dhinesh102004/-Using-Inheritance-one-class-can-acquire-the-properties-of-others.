# -Using-Inheritance-one-class-can-acquire-the-properties-of-others.
```
class Animal {
    void eat() {
        System.out.println("This animal eats food.");
    }
}

class Dog extends Animal {
    void bark() {
        System.out.println("The dog barks.");
    }
}

public class InheritanceExample {
    public static void main(String[] args) {
        Dog myDog = new Dog();
        myDog.eat();
        myDog.bark();
    }
}

```
#output
![280739079-b0805c3b-b02f-4262-abc1-e59a0d1ebbf9](https://github.com/dhinesh102004/-Using-Inheritance-one-class-can-acquire-the-properties-of-others./assets/142372008/c5f44d05-8fb1-480c-9933-e667ef1bb599)
