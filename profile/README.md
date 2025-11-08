# LiquidJava - Extending Java with Liquid Types

![LiquidJava Banner](banner.gif)

## Welcome to LiquidJava!

LiquidJava is an additional type checker for Java, based on **liquid types** and **typestates**, which provides additional safety guarantees to Java programs through **refinements** at compile time.

**Example:**

```java
@Refinement("a > 0")
int a = 3; // okay
a = -8; // type error!
```

Learn more in the [LiquidJava website](https://liquid-java.github.io).
