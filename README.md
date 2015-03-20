# CoffeeMaker Dagger2-Sample

## Usage

```bash
./gradlew execute
```

## Getting Start

Main: [src/main/java/coffee/CoffeeApp.java](src/main/java/coffee/CoffeeApp.java)

```java
Coffee coffee = Dagger_CoffeeApp_Coffee.create();
coffee.maker().brew();
```

## See Also

* Import from https://github.com/google/dagger/tree/master/examples/simple/src/main/java/coffee
* Official CoffeeMaker Documentation: http://google.github.io/dagger/
