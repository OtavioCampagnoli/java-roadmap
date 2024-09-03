### Basic Syntax in Java

- **Case Sensitivity**: Java is case-sensitive, so `hello` and `Hello` are treated as distinct identifiers.
  ```java
  int hello = 5;
  int Hello = 10;
  // 'hello' and 'Hello' are different variables
  ```

- **Class Names**: Class names should start with an uppercase letter and match the file name.
  ```java
  // File name: Human.java
  public class Human {
      // Class content
  }
  ```

- **Method Names**: Method names should start with a lowercase letter.
  ```java
  public class Human {
      public void sleep() {
          // Method content
      }
      
      public void getUp() {
          // Method content
      }
  }
  ```

- **Program File Name**: The file name should exactly match the class name.
  ```java
  // For class Human, the file name must be Human.java
  ```

- **Class**: A fundamental building block in Java that defines a blueprint for objects.
  ```java
  public class Car {
      // Attributes and methods of Car
  }
  ```

- **Identifiers**: Names given to classes, methods, and variables.
  ```java
  int number; // Variable identifier
  public void drive() {} // Method identifier
  ```

- **Keywords**: Reserved words in Java with predefined meanings.
  ```java
  int class = 5; // 'class' is a keyword and cannot be used as an identifier
  ```

- **Comments**: Used to annotate the code, ignored by the compiler.
  ```java
  // This is a single-line comment
  
  /*
   This is a multi-line comment
  */
  ```