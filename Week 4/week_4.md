# Week 4: Functions and Built-in Functions in Processing

## Session Plan

### Introduction
- Brief overview of functions
- Importance of functions in programming

### Functions in Processing
- Definition and syntax of functions
- How to define a function in Processing
- Example:
    ```java
    void setup() {
        size(400, 400);
        background(255);
        drawCircle(200, 200, 50);
    }

    void drawCircle(float x, float y, float diameter) {
        ellipse(x, y, diameter, diameter);
    }
    ```

### Built-in Functions in Processing
- Explanation of built-in functions
- Commonly used built-in functions in Processing
    - `size()`
    - `background()`
    - `ellipse()`
    - `rect()`
    - `line()`
- Example:
    ```java
    void setup() {
        size(400, 400);
        background(255);
        drawShapes();
    }

    void drawShapes() {
        ellipse(100, 100, 50, 50);
        rect(200, 200, 50, 50);
        line(300, 300, 350, 350);
    }
    ```

### Hands-on Examples
- Example 1: Drawing a house using functions
    ```java
    void setup() {
        size(400, 400);
        background(255);
        drawHouse(100, 200);
    }

    void drawHouse(float x, float y) {
        rect(x, y, 100, 100); // House base
        triangle(x, y, x + 50, y - 50, x + 100, y); // Roof
    }
    ```
- Example 2: Creating a pattern with built-in functions
    ```java
    void setup() {
        size(400, 400);
        background(255);
        drawPattern();
    }

    void drawPattern() {
        for (int i = 0; i < width; i += 50) {
            for (int j = 0; j < height; j += 50) {
                ellipse(i, j, 40, 40);
            }
        }
    }
    ```

### Q&A Session
- Open floor for questions
- Discuss any challenges faced during the hands-on examples

### Conclusion
- Recap of key points
- Importance of practicing functions and built-in functions

### Handouts
- Provide code examples used during the session
- Additional exercises for practice
