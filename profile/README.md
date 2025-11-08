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

You can find out more about LiquidJava in the following resources:

* [LiquidJava Website](https://catarinagamboa.github.io/liquidjava.html)
* [VS Code Extension (Marketplace)](https://marketplace.visualstudio.com/items?itemName=AlcidesFonseca.liquid-java)
* [VS Code Extension (Source Code)](https://github.com/liquid-java/vscode-liquidjava)
* [LiquidJava Examples](https://github.com/liquid-java/liquidjava-examples)
* [LiquidJava External Libraries Examples](https://github.com/liquid-java/liquid-java-external-libs)
<!-- * [Formalization of LiquidJava](https://github.com/liquid-java/liquidjava-formalization) - not opensource yet -->
