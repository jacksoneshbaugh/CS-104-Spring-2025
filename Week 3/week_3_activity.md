# Week 3 Activity: Variable Scope and Lifetime in Processing

## Questions

1. **Describe the difference between local and global variables.**

2. **What is the lifetime of a variable?**  

3. **Given the following code, what will print?**  

    ```java
    int x = 10;

    void setup() {
        int x = 5;
        println(x);
    }

    void draw() {
        println(x);
    }
    ```

4. **What is the scope of each variable?**  

    ```java
    int a = 20;

    void setup() {
        int b = 15;
        println(b);
    }

    void draw() {
        println(a);
    }
    ```

5. **Predict and Fix the Error**  
   What will happen when you run this code? If there is an error, explain why and fix it.

    ```java
    void setup() {
        println(num);
    }

    void draw() {
        int num = 100;
        println(num);
    }
    ```

6. **Modifying a Variable in Different Scopes**  
   What will be printed in the console when you run this code?

    ```java
    int counter = 0;

    void setup() {
        counter = counter + 5;
        println(counter);
    }

    void draw() {
        int counter = 10;
        counter = counter + 1;
        println(counter);
    }
    ```

   **Challenge:**  
   Modify the code so that `counter` always increases globally and does not reset inside `draw()`.
