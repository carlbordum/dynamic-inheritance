# dynamic inheritance
A true classic when it comes to OOP patterns; refer to your text book.


``` python
import random


class Cat:
    def speak(self):
        print('Meow!')


class Dog:
    def speak(self):
        print('Woof!')


class RandomAnimal(random.choice((Cat, Dog))):
    pass


if __name__ == '__main__':
    RandomAnimal().speak()

```

``` python
Woof!
```


(please let me know (e.g. submit pr) if you have other awesome ideas)
