# Q1: What is JVM, JRE, and JDK in Java?

## Explanation

| Term | Full Form | Role |
|------|-----------|------|
| JVM  | Java Virtual Machine | Runs Java bytecode |
| JRE  | Java Runtime Environment | JVM + Core Libraries |
| JDK  | Java Development Kit | JRE + Compiler + Dev Tools |

---

## Diagram

```mermaid
flowchart LR
    A[JDK] --> B[JRE]
    B --> C[JVM]
```
---

## Code Example

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Java runs on the JVM!");
    }
}
```