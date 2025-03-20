
# 📘 Introduction to Java Programming

## 🔵 Introduction to Java

- **Java** is a high-level, object-oriented programming language developed by **Sun Microsystems** (now owned by **Oracle**).
- It was designed to have as few implementation dependencies as possible, making it a **portable** and **platform-independent** language.
- Java programs can be run on any device with the **Java Virtual Machine (JVM)**, following the "Write Once, Run Anywhere" (WORA) philosophy.

### 🔑 Key Features of Java:
- Object-Oriented
- Platform Independent
- Secure
- Simple and easy to learn
- Robust (strong memory management and exception handling)
- Multithreaded (can perform multiple tasks simultaneously)
- Distributed (supports networking)

---

## 🟢 Basic Java Concepts

1. **Class** – Blueprint for creating objects.
2. **Object** – Instance of a class containing state (fields) and behavior (methods).
3. **Method** – A function defined inside a class.
4. **Main Method** – The entry point of every Java application:
   ```java
   public static void main(String[] args)
   ```

### 💡 Java Program Structure:
```java
public class MyProgram {
    public static void main(String[] args) {
        // Code to execute
    }
}
```

---

## 🟣 What are `.java`, `.class`, Object, and JVM?

### **.java File**
- A file containing the source code of a Java program.
- Always ends with the `.java` extension.
- Example: `HelloWorld.java`

### **.class File**
- After compiling a `.java` file using the `javac` compiler, you get a `.class` file.
- The `.class` file contains **bytecode** which is executed by the JVM.
- Example: `HelloWorld.class`

### **Object**
- An **object** is an instance of a class.
- Each object has:
  - **Fields/Attributes** (state)
  - **Methods** (behavior)

### **JVM (Java Virtual Machine)**
- A virtual machine that executes the bytecode from `.class` files.
- Provides platform independence.

### **Java Development Process:**
```
1. Write source code in `.java` file ➡️
2. Compile with `javac` ➡️
3. Generate `.class` bytecode ➡️
4. Execute with `java` command (JVM runs it)
```

---

## 🟡 Creating a Java Program (Simple Example)

### ✅ Example 1: Hello World Program

**Step 1:** Write the program in `HelloWorld.java`
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, world!");
    }
}
```

**Step 2:** Compile the program:
```bash
javac HelloWorld.java
```

**Step 3:** Run the compiled program:
```bash
java HelloWorld
```

**Output:**
```
Hello, world!
```

---

## 🟠 Java Variables and Data Types

### **What is a Variable?**
- A variable is a container that holds data that can be changed during the execution of a program.

### **Declaring a Variable:**
```java
dataType variableName = value;
```

### **Java Data Types**

| Data Type   | Description                  | Example           |
|-------------|------------------------------|-------------------|
| `int`       | Integer (whole numbers)      | `int age = 20;`   |
| `double`    | Floating-point numbers       | `double pi = 3.14;`|
| `char`      | Single character             | `char grade = 'A';`|
| `boolean`   | True or False value          | `boolean isJavaFun = true;`|
| `String`    | Sequence of characters       | `String name = "Alice";`|

### **Example:**

```java
public class VariablesExample {
    public static void main(String[] args) {
        int age = 20;
        double pi = 3.14;
        char grade = 'A';
        boolean isJavaFun = true;
        String name = "Alice";

        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("PI value: " + pi);
        System.out.println("Grade: " + grade);
        System.out.println("Is Java Fun? " + isJavaFun);
    }
}
```

**Output:**
```
Name: Alice
Age: 20
PI value: 3.14
Grade: A
Is Java Fun? true
```

---

## 📝 Summary:
- Java is platform-independent and object-oriented.
- Source code is written in `.java` files and compiled to `.class` bytecode.
- JVM executes the `.class` files.
- Variables in Java hold data, and data types define what kind of data a variable can hold.
