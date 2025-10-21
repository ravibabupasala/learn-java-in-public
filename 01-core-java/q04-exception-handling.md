# Q4: How does exception handling work in Java?

## Explanation

- Exceptions are **runtime errors** that can be handled using try-catch blocks.
- **Types of Exceptions**: Checked vs Unchecked

| Type | Example | Handled By |
|------|--------|------------|
| Checked | IOException | try-catch or throws |
| Unchecked | ArithmeticException | Optional |

---

## Code Example

```java
public class ExceptionDemo {
    public static void main(String[] args) {
        try {
            int result = 10 / 0;
        } catch (ArithmeticException e) {
            System.out.println("Cannot divide by zero!");
        } finally {
            System.out.println("Execution completed.");
        }
    }
}