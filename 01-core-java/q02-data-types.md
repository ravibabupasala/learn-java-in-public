```markdown
# Q2: What are primitive and reference data types in Java?

## Explanation

- **Primitive Types**: byte, short, int, long, float, double, char, boolean
- **Reference Types**: Objects, Arrays, Interfaces, Strings

| Feature | Primitive | Reference |
|---------|----------|-----------|
| Stored in | Stack | Heap |
| Default Value | 0 / false | null |
| Example | int x = 5; | String s = "Hello"; |

---

## Code Example

```java
int age = 25; // primitive
String name = "Ravi"; // reference

System.out.println(name + " is " + age + " years old.");