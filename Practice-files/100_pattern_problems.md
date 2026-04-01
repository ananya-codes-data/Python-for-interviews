# 🐍 100 Python Pattern Problems

### For Logic Building — Pattern Visualization Included

> **Default size:** `n = 7` for all patterns unless stated otherwise.
>
> - 🔤 **Alphabet patterns** → `n = 5` (26 letter limit)
> - 🔢 **Pascal's Triangle & Fibonacci Triangle** → `n = 5`
>
> Your job: write the Python code to reproduce each pattern!

## 🟢 Level 1 — Basic Loop Patterns (1–20)
>
> **Focus:** Simple `for` loops

### 1. Square Star Pattern

`🟢 Easy` | `n = 7`

```text
* * * * * * *
* * * * * * *
* * * * * * *
* * * * * * *
* * * * * * *
* * * * * * *
* * * * * * *
```

### 2. Rectangle Star Pattern

`🟢 Easy` | `rows = 4, cols = 7`

```text
* * * * * * *
* * * * * * *
* * * * * * *
* * * * * * *
```

### 3. Vertical Star Line

`🟢 Easy` | `n = 7`

```text
*
*
*
*
*
*
*
```

### 4. Horizontal Star Line

`🟢 Easy` | `n = 7`

```text
* * * * * * *
```

### 5. Increasing Star Triangle

`🟢 Easy` | `n = 7`

```text
*
* *
* * *
* * * *
* * * * *
* * * * * *
* * * * * * *
```

### 6. Decreasing Star Triangle

`🟢 Easy` | `n = 7`

```text
* * * * * * *
* * * * * *
* * * * *
* * * *
* * *
* *
*
```

### 7. Right-Shifted Triangle

`🟢 Easy` | `n = 7`

```text
            *
          * *
        * * *
      * * * *
    * * * * *
  * * * * * *
* * * * * * *
```

### 8. Left Diagonal Star

`🟢 Easy` | `n = 7`

```text
*
* *
* * *
* * * *
* * * * *
* * * * * *
* * * * * * *
```

### 9. Right Diagonal Star

`🟢 Easy` | `n = 7`

```text
            *
          * *
        * * *
      * * * *
    * * * * *
  * * * * * *
* * * * * * *
```

### 10. Star Ladder Pattern

`🟢 Easy` | `n = 4`

```text
*
*
* *
* *
* * *
* * *
* * * *
* * * *
```

### 11. Star Staircase

`🟢 Easy` | `n = 7`

```text
*
* *
* * *
* * * *
* * * * *
* * * * * *
* * * * * * *
```text

### 12. Fixed Column Star Pattern

`🟢 Easy` | `rows = 7, cols = 3`

```text
* * *
* * *
* * *
* * *
* * *
* * *
* * *
```

### 13. Increasing Number Triangle

`🟢 Easy` | `n = 7`

```text
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
1 2 3 4 5 6
1 2 3 4 5 6 7
```

### 14. Decreasing Number Triangle

`🟢 Easy` | `n = 7`

```text
1 2 3 4 5 6 7
1 2 3 4 5 6
1 2 3 4 5
1 2 3 4
1 2 3
1 2
1
```

### 15. Alphabet Vertical Pattern

`🟢 Easy` | `n = 5`

```text
A
B
C
D
E
```

### 16. Alphabet Triangle

`🟢 Easy` | `n = 5`

```text
A
A B
A B C
A B C D
A B C D E
```

### 17. Repeating Number Triangle

`🟢 Easy` | `n = 7`

```text
1
2 2
3 3 3
4 4 4 4
5 5 5 5 5
6 6 6 6 6 6
7 7 7 7 7 7 7
```

### 18. Repeating Alphabet Triangle

`🟢 Easy` | `n = 5`

```text
A
B B
C C C
D D D D
E E E E E
```

### 19. Solid Square Numbers

`🟢 Easy` | `n = 7`

```text
1 2 3 4 5 6 7
1 2 3 4 5 6 7
1 2 3 4 5 6 7
1 2 3 4 5 6 7
1 2 3 4 5 6 7
1 2 3 4 5 6 7
1 2 3 4 5 6 7
```

### 20. Alternating Star Row

`🟢 Easy` | `n = 7`

```text
* * * * * * *
- - - - - - -
* * * * * * *
- - - - - - -
* * * * * * *
- - - - - - -
* * * * * * *
```

## 🟡 Level 2 — Nested Loop Logic (21–40)
>
> **Focus:** Nested loops

### 21. Center Pyramid

`🟡 Medium` | `n = 7`

```text
            *
          * * *
        * * * * *
      * * * * * * *
    * * * * * * * * *
  * * * * * * * * * * *
* * * * * * * * * * * * *
```

### 22. Reverse Pyramid

`🟡 Medium` | `n = 7`

```text
* * * * * * * * * * * * *
  * * * * * * * * * * *
    * * * * * * * * *
      * * * * * * *
        * * * * *
          * * *
            *
```

### 23. Half Diamond

`🟡 Medium` | `n = 7`

```text
*
* *
* * *
* * * *
* * * * *
* * * * * *
* * * * * * *
* * * * * *
* * * * *
* * * *
* * *
* *
*
```

### 24. Full Diamond

`🟡 Medium` | `n = 7`

```text
            *
          * * *
        * * * * *
      * * * * * * *
    * * * * * * * * *
  * * * * * * * * * * *
* * * * * * * * * * * * *
  * * * * * * * * * * *
    * * * * * * * * *
      * * * * * * *
        * * * * *
          * * *
            *
```

### 25. Hollow Square

`🟡 Medium` | `n = 7`

```text
* * * * * * *
*           *
*           *
*           *
*           *
*           *
* * * * * * *
```

### 26. Hollow Rectangle

`🟡 Medium` | `rows = 4, cols = 7`

```text
* * * * * * *
*           *
*           *
* * * * * * *
```

### 27. Hollow Triangle

`🟡 Medium` | `n = 7`

```text
*
* *
*   *
*     *
*       *
*         *
* * * * * * *
```

### 28. X Pattern

`🟡 Medium` | `n = 7`

```text
*           *
  *       *
    *   *
      *
    *   *
  *       *
*           *
```

### 29. Plus Sign Pattern

`🟡 Medium` | `n = 7`

```text
      *
      *
      *
* * * * * * *
      *
      *
      *
```

### 30. Checkerboard Pattern

`🟡 Medium` | `n = 7`

```text
* - * - * - *
- * - * - * -
* - * - * - *
- * - * - * -
* - * - * - *
- * - * - * -
* - * - * - *
```

### 31. Star Pyramid with Spaces

`🟡 Medium` | `n = 7`

```text
            *
          * * *
        * * * * *
      * * * * * * *
    * * * * * * * * *
  * * * * * * * * * * *
* * * * * * * * * * * * *
```

### 32. Number Pyramid

`🟡 Medium` | `n = 7`

```text
            1
          1 2 1
        1 2 3 2 1
      1 2 3 4 3 2 1
    1 2 3 4 5 4 3 2 1
  1 2 3 4 5 6 5 4 3 2 1
1 2 3 4 5 6 7 6 5 4 3 2 1
```

### 33. Alphabet Pyramid

`🟡 Medium` | `n = 5`

```text
        A
      A B A
    A B C B A
  A B C D C B A
A B C D E D C B A
```

### 34. Reverse Number Pyramid

`🟡 Medium` | `n = 7`

```text
1 2 3 4 5 6 7 6 5 4 3 2 1
  1 2 3 4 5 6 5 4 3 2 1
    1 2 3 4 5 4 3 2 1
      1 2 3 4 3 2 1
        1 2 3 2 1
          1 2 1
            1
```

### 35. Reverse Alphabet Pyramid

`🟡 Medium` | `n = 5`

```text
A B C D E D C B A
  A B C D C B A
    A B C B A
      A B A
        A
```

### 36. Diamond Number Pattern

`🟡 Medium` | `n = 7`

```text
            1
          2 1 2
        3 2 1 2 3
      4 3 2 1 2 3 4
    5 4 3 2 1 2 3 4 5
  6 5 4 3 2 1 2 3 4 5 6
7 6 5 4 3 2 1 2 3 4 5 6 7
  6 5 4 3 2 1 2 3 4 5 6
    5 4 3 2 1 2 3 4 5
      4 3 2 1 2 3 4
        3 2 1 2 3
          2 1 2
            1
```

### 37. Diamond Alphabet Pattern

`🟡 Medium` | `n = 5`

```text
        E
      D E D
    C D E D C
  B C D E D C B
A B C D E D C B A
  B C D E D C B
    C D E D C
      D E D
        E
```

### 38. Pyramid with Even Numbers

`🟡 Medium` | `n = 7`

```text
            2
          2 4 2
        2 4 6 4 2
      2 4 6 8 6 4 2
    2 4 6 8 10 8 6 4 2
  2 4 6 8 10 12 10 8 6 4 2
2 4 6 8 10 12 14 12 10 8 6 4 2
```

### 39. Pyramid with Odd Numbers

`🟡 Medium` | `n = 7`

```text
            1
          1 3 1
        1 3 5 3 1
      1 3 5 7 5 3 1
    1 3 5 7 9 7 5 3 1
  1 3 5 7 9 11 9 7 5 3 1
1 3 5 7 9 11 13 11 9 7 5 3 1
```

### 40. Alternating Binary Pyramid

`🟡 Medium` | `n = 7`

```text
            1
          1 0 1
        1 0 1 0 1
      1 0 1 0 1 0 1
    1 0 1 0 1 0 1 0 1
  1 0 1 0 1 0 1 0 1 0 1
1 0 1 0 1 0 1 0 1 0 1 0 1
```

## 🟠 Level 3 — Conditional Logic (41–60)
>
> **Focus:** `if` inside loops

### 41. Diagonal Star Square

`🟠 Medium-Hard` | `n = 7`

```text
*
  *
    *
      *
        *
          *
            *
```

### 42. Cross Star Square

`🟠 Medium-Hard` | `n = 7`

```text
*           *
  *       *
    *   *
      *
    *   *
  *       *
*           *
```

### 43. Hollow Diamond

`🟠 Medium-Hard` | `n = 7`

```text
            *
          *   *
        *       *
      *           *
    *               *
  *                   *
*                       *
  *                   *
    *               *
      *           *
        *       *
          *   *
            *
```

### 44. Hollow Pyramid

`🟠 Medium-Hard` | `n = 7`

```text
            *
          *   *
        *       *
      *           *
    *               *
  *                   *
* * * * * * * * * * * * *
```

### 45. Border-Only Pyramid

`🟠 Medium-Hard` | `n = 7`

```text
            *
          * *
        *   *
      *     *
    *       *
  *         *
* * * * * * *
```

### 46. Alternating Star Triangle

`🟠 Medium-Hard` | `n = 7`

```text
*
* -
* - *
* - * -
* - * - *
* - * - * -
* - * - * - *
```

### 47. Zig-Zag Star Pattern

`🟠 Medium-Hard` | `n = 9`

```text
  *   *   *   *   *
*   *   *   *   *
  *   *   *   *   *
```

### 48. Checkerboard Numbers

`🟠 Medium-Hard` | `n = 7`

```text
1 2 1 2 1 2 1
2 1 2 1 2 1 2
1 2 1 2 1 2 1
2 1 2 1 2 1 2
1 2 1 2 1 2 1
2 1 2 1 2 1 2
1 2 1 2 1 2 1
```

### 49. Checkerboard Alphabets

`🟠 Medium-Hard` | `n = 5`

```text
A B A B A
B A B A B
A B A B A
B A B A B
A B A B A
```

### 50. Hollow Number Square

`🟠 Medium-Hard` | `n = 7`

```text
1 2 3 4 5 6 7
2           7
3           7
4           7
5           7
6           7
1 2 3 4 5 6 7
```

### 51. Hollow Alphabet Square

`🟠 Medium-Hard` | `n = 5`

```text
A B C D E
B       E
C       E
D       E
A B C D E
```

### 52. Diagonal Number Square

`🟠 Medium-Hard` | `n = 7`

```text
1
  2
    3
      4
        5
          6
            7
```

### 53. Diagonal Alphabet Square

`🟠 Medium-Hard` | `n = 5`

```text
A
  B
    C
      D
        E
```

### 54. Star Pyramid with Hollow Center

`🟠 Medium-Hard` | `n = 7`

```text
            *
          * * *
        * *   * *
      * *       * *
    * *           * *
  * *               * *
* * * * * * * * * * * * *
```

### 55. Pyramid with Alternating Numbers

`🟠 Medium-Hard` | `n = 7`

```text
            1
          2 1 2
        1 2 1 2 1
      2 1 2 1 2 1 2
    1 2 1 2 1 2 1 2 1
  2 1 2 1 2 1 2 1 2 1 2
1 2 1 2 1 2 1 2 1 2 1 2 1
```

### 56. Alphabet Alternating Rows

`🟠 Medium-Hard` | `n = 5`

```text
A B C D E
1 2 3 4 5
A B C D E
1 2 3 4 5
A B C D E
```

### 57. Reverse Alternating Pyramid

`🟠 Medium-Hard` | `n = 7`

```text
* * * * * * * * * * * * *
  * - * - * - * - * - *
    * - * - * - * - *
      * - * - * - *
        * - * - *
          * - *
            *
```

### 58. Triangle with Mirrored Numbers

`🟠 Medium-Hard` | `n = 7`

```text
1
1 2 1
1 2 3 2 1
1 2 3 4 3 2 1
1 2 3 4 5 4 3 2 1
1 2 3 4 5 6 5 4 3 2 1
1 2 3 4 5 6 7 6 5 4 3 2 1
```

### 59. Triangle with Mirrored Alphabets

`🟠 Medium-Hard` | `n = 5`

```text
A
A B A
A B C B A
A B C D C B A
A B C D E D C B A
```

### 60. Triangle with Alternating Characters

`🟠 Medium-Hard` | `n = 7`

```text
*
* #
* # *
* # * #
* # * # *
* # * # * #
* # * # * # *
```

## 🔵 Level 4 — Variable Tracking (61–80)
>
> **Focus:** Running counters

### 61. Floyd's Triangle

`🔵 Hard` | `n = 7`

```text
1
2  3
4  5  6
7  8  9  10
11 12 13 14 15
16 17 18 19 20 21
22 23 24 25 26 27 28
```

### 62. Reverse Floyd's Triangle

`🔵 Hard` | `n = 7`

```text
22 23 24 25 26 27 28
16 17 18 19 20 21
11 12 13 14 15
7  8  9  10
4  5  6
2  3
1
```

### 63. Continuous Number Square

`🔵 Hard` | `n = 7`

```text
1  2  3  4  5  6  7
8  9  10 11 12 13 14
15 16 17 18 19 20 21
22 23 24 25 26 27 28
29 30 31 32 33 34 35
36 37 38 39 40 41 42
43 44 45 46 47 48 49
```

### 64. Continuous Alphabet Square

`🔵 Hard` | `n = 5`

```text
A B C D E
F G H I J
K L M N O
P Q R S T
U V W X Y
```

### 65. Snake Number Matrix

`🔵 Hard` | `n = 7`

```text
1  2  3  4  5  6  7
14 13 12 11 10 9  8
15 16 17 18 19 20 21
28 27 26 25 24 23 22
29 30 31 32 33 34 35
42 41 40 39 38 37 36
43 44 45 46 47 48 49
```

### 66. Snake Alphabet Matrix

`🔵 Hard` | `n = 5`

```text
A  B  C  D  E
J  I  H  G  F
K  L  M  N  O
T  S  R  Q  P
U  V  W  X  Y
```

### 67. Increasing Odd Number Triangle

`🔵 Hard` | `n = 7`

```text
1
3  5
7  9  11
13 15 17 19
21 23 25 27 29
31 33 35 37 39 41
43 45 47 49 51 53 55
```

### 68. Increasing Even Number Triangle

`🔵 Hard` | `n = 7`

```text
2
4  6
8  10 12
14 16 18 20
22 24 26 28 30
32 34 36 38 40 42
44 46 48 50 52 54 56
```

### 69. Pascal's Triangle

`🔵 Hard` | `n = 5`

```text
        1
      1   1
    1   2   1
  1   3   3   1
1   4   6   4   1
```

### 70. Pascal Pyramid Centered

`🔵 Hard` | `n = 5`

```text
        1
       1 1
      1 2 1
     1 3 3 1
    1 4 6 4 1
```

### 71. Multiplication Table Triangle

`🔵 Hard` | `n = 7`

```text
1
2  4
3  6  9
4  8  12 16
5  10 15 20 25
6  12 18 24 30 36
7  14 21 28 35 42 49
```

### 72. Multiplication Square Pattern

`🔵 Hard` | `n = 7`

```text
1  2  3  4  5  6  7
2  4  6  8  10 12 14
3  6  9  12 15 18 21
4  8  12 16 20 24 28
5  10 15 20 25 30 35
6  12 18 24 30 36 42
7  14 21 28 35 42 49
```

### 73. Fibonacci Triangle

`🔵 Hard` | `n = 5`

```text
0
1  1
2  3  5
8  13 21 34
55 89 144 233 377
```

### 74. Incremental Alphabet Pyramid

`🔵 Hard` | `n = 5`

```text
        A
      B C B
    C D E D C
  D E F G F E D
E F G H I H G F E
```

### 75. Reverse Incremental Alphabet Pyramid

`🔵 Hard` | `n = 5`

```text
E F G H I H G F E
  D E F G F E D
    C D E D C
      B C B
        A
```

### 76. Number Spiral Start

`🔵 Hard` | `3×3`

```text
1 2 3
8 9 4
7 6 5
```

### 77. Number Spiral Square

`🔵 Hard` | `4×4`

```text
1  2  3  4
12 13 14  5
11 16 15  6
10  9  8  7
```

### 78. Number Diamond Incremental

`🔵 Hard` | `n = 7`

```text
            1
          2 3 4
        5 6 7 8 9
      10 11 12 13 14 15 16
    17 18 19 20 21 22 23 24 25
  26 27 28 29 30 31 32 33 34 35 36
37 38 39 40 41 42 43 44 45 46 47 48 49
```

### 79. Alphabet Diamond Incremental

`🔵 Hard` | `n = 5`

```text
        A
      B C D
    E F G H I
  J K L M N O P
Q R S T U V W X Y
```

### 80. Triangle with Global Counter

`🔵 Hard` | `n = 7`

```text
1
2  3
4  5  6
7  8  9  10
11 12 13 14 15
16 17 18 19 20 21
22 23 24 25 26 27 28
```

## 🔴 Level 5 — Advanced Interview Patterns (81–100)
>
> **Focus:** Complex logic

### 81. Butterfly Pattern

`🔴 Very Hard` | `n = 7`

```text
*                         *
* *                     * *
* * *                 * * *
* * * *             * * * *
* * * * *         * * * * *
* * * * * *     * * * * * *
* * * * * * * * * * * * * *
* * * * * *     * * * * * *
* * * * *         * * * * *
* * * *             * * * *
* * *                 * * *
* *                     * *
*                         *
```

### 82. Reverse Butterfly

`🔴 Very Hard` | `n = 7`

```text
* * * * * * * * * * * * * *
* * * * * *     * * * * * *
* * * * *         * * * * *
* * * *             * * * *
* * *                 * * *
* *                     * *
*                         *
* *                     * *
* * *                 * * *
* * * *             * * * *
* * * * *         * * * * *
* * * * * *     * * * * * *
* * * * * * * * * * * * * *
```

### 83. Sandglass Pattern

`🔴 Very Hard` | `n = 7`

```text
* * * * * * * * * * * * *
  * * * * * * * * * * *
    * * * * * * * * *
      * * * * * * *
        * * * * *
          * * *
            *
          * * *
        * * * * *
      * * * * * * *
    * * * * * * * * *
  * * * * * * * * * * *
* * * * * * * * * * * * *
```

### 84. Reverse Sandglass

`🔴 Very Hard` | `n = 7`

```text
            *
          * * *
        * * * * *
      * * * * * * *
    * * * * * * * * *
  * * * * * * * * * * *
* * * * * * * * * * * * *
  * * * * * * * * * * *
    * * * * * * * * *
      * * * * * * *
        * * * * *
          * * *
            *
```

### 85. Hourglass Pattern

`🔴 Very Hard` | `n = 7`

```text
* * * * * * * * * * * * *
  * * * * * * * * * * *
    * * * * * * * * *
      * * * * * * *
    * * * * * * * * *
  * * * * * * * * * * *
* * * * * * * * * * * * *
```

### 86. Hollow Butterfly Pattern

`🔴 Very Hard` | `n = 7`

```text
*                         *
* *                     * *
*   *                 *   *
*     *             *     *
*       *         *       *
*         *     *         *
*           * *           *
*         *     *         *
*       *         *       *
*     *             *     *
*   *                 *   *
* *                     * *
*                         *
```

### 87. Zig-Zag 3-Row Star Pattern

`🔴 Very Hard` | `n = 9`

```text
  *   *   *   *   *
*   *   *   *   *
  *   *   *   *   *
```

### 88. Spiral Number Matrix

`🔴 Very Hard` | `5×5`

```text
 1  2  3  4  5
16 17 18 19  6
15 24 25 20  7
14 23 22 21  8
13 12 11 10  9
```

### 89. Spiral Alphabet Matrix

`🔴 Very Hard` | `4×4`

```text
A  B  C  D
L  M  N  E
K  P  O  F
J  I  H  G
```

### 90. Palindrome Number Pyramid

`🔴 Very Hard` | `n = 7`

```text
            1
          2 1 2
        3 2 1 2 3
      4 3 2 1 2 3 4
    5 4 3 2 1 2 3 4 5
  6 5 4 3 2 1 2 3 4 5 6
7 6 5 4 3 2 1 2 3 4 5 6 7
```

### 91. Palindrome Alphabet Pyramid

`🔴 Very Hard` | `n = 5`

```text
        E
      D E D
    C D E D C
  B C D E D C B
A B C D E D C B A
```

### 92. Hollow Palindrome Pyramid

`🔴 Very Hard` | `n = 7`

```text
            *
          *   *
        *       *
      *           *
    *               *
  *                   *
* * * * * * * * * * * * *
```

### 93. Centered Number Diamond

`🔴 Very Hard` | `n = 7`

```text
            1
          1 2 1
        1 2 3 2 1
      1 2 3 4 3 2 1
    1 2 3 4 5 4 3 2 1
  1 2 3 4 5 6 5 4 3 2 1
1 2 3 4 5 6 7 6 5 4 3 2 1
  1 2 3 4 5 6 5 4 3 2 1
    1 2 3 4 5 4 3 2 1
      1 2 3 4 3 2 1
        1 2 3 2 1
          1 2 1
            1
```

### 94. Centered Alphabet Diamond

`🔴 Very Hard` | `n = 5`

```text
        A
      A B A
    A B C B A
  A B C D C B A
A B C D E D C B A
  A B C D C B A
    A B C B A
      A B A
        A
```

### 95. Pascal Diamond

`🔴 Very Hard` | `n = 5`

```text
         1
       1   1
     1   2   1
   1   3   3   1
 1   4   6   4   1
   1   3   3   1
     1   2   1
       1   1
         1
```

### 96. Pyramid with Skipping Numbers

`🔴 Very Hard` | `n = 7` *(skip every 3rd)*

```text
            1
          1 2 1
        1 2 4 2 1
      1 2 4 5 4 2 1
    1 2 4 5 7 5 4 2 1
  1 2 4 5 7 8 7 5 4 2 1
1 2 4 5 7 8 10 8 7 5 4 2 1
```

### 97. Pyramid with Prime Numbers

`🔴 Very Hard` | `n = 5`

```text
        2
      3 5 3
    7 11 13 11 7
  17 19 23 29 23 19 17
31 37 41 43 47 43 41 37 31
```

### 98. Pattern Using While Loop Only

`🔴 Very Hard` | `n = 7`

```text
*
* *
* * *
* * * *
* * * * *
* * * * * *
* * * * * * *
* * * * * *
* * * * *
* * * *
* * *
* *
*
```

> ⚠️ **Constraint:** Use **only** `while` loops — no `for` loops allowed.

### 99. Pattern Using Break and Continue

`🔴 Very Hard` | `n = 7`

```text
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
1 2 3 4 5 6
1 2 3 4 5 6 7
```

> ⚠️ **Constraint:** Must use both `break` and `continue` statements meaningfully in your solution.

### 100. Custom Mixed Pattern (Stars + Numbers + Alphabets)

`🔴 Very Hard` | `n = 7`

```text
A * 1 * A * 1
* B * 2 * B *
1 * C * 3 * C
* 2 * D * 4 *
A * 3 * E * 5
* B * 4 * F *
1 * C * 5 * G
```

> ⚠️ **The ultimate challenge** — combine stars, numbers, and alphabets using conditionals and nested loops.

## 📊 Summary Table

| Level | Problems | n | Focus |
|-|-||-|
| 🟢 Level 1 | 1–20   | 7 (alphabet → 5) | Simple `for` loops |
| 🟡 Level 2 | 21–40  | 7 (alphabet → 5) | Nested loops |
| 🟠 Level 3 | 41–60  | 7 (alphabet → 5) | `if` inside loops |
| 🔵 Level 4 | 61–80  | 7 (alphabet → 5, Pascal/Fib → 5) | Variable tracking |
| 🔴 Level 5 | 81–100 | 7 (alphabet → 5) | Advanced / Interview |

> 💡 **Tip:** Stuck on a pattern? Try `n = 3` first to understand the structure, then scale up!

## 🧠 The Universal Pattern Solving Framework

### Step 1 — Observe the pattern manually (n = 3 or n = 4)

Before writing a single line of code, shrink the pattern to a small size and **stare at it**.
Ask yourself:

- How many rows are there?
- What changes row by row?
- What stays the same?

### Step 2 — Build a row-column table

This is the **most important trick**. Give every position a row number `i` and column number `j` (starting from 0 or 1), then find the relationship.

For example, Increasing Star Triangle:

```text
Row 1 → 1 star
Row 2 → 2 stars
Row 3 → 3 stars
```

You immediately see: **number of stars = row number (i)**. That's your inner loop range.

### Step 3 — Break every row into 3 zones

Almost every pattern row has up to 3 parts:

```text
[spaces]  [content]  [more spaces or mirrored content]
```

Train yourself to always ask — *does this row have leading spaces? does it have trailing content?* Each zone becomes its own inner loop or print statement.

### Step 4 — Ask these 5 questions for every pattern

| Question | What it tells you |
|||
| How many rows? | Your outer loop range |
| What prints on each row? | Your inner loop content |
| Is there leading space? | You need a space loop before content |
| Does content mirror? | You need a second inner loop going backwards |
| Does something increment globally? | You need a counter variable outside all loops |

### Step 5 — Identify the pattern type

| Type | Key Signal | Example Problems |
||||
| **Simple repeat** | Same thing per row | 1–12 |
| **Increasing/decreasing** | Count changes with `i` | 5, 6, 13, 14 |
| **Centered pyramid** | Spaces = `n - i`, stars = `2i - 1` | 21, 22, 31 |
| **Hollow shape** | Print only on borders (`j == 1` or `j == i`) | 25, 27, 44 |
| **Mirrored content** | Two inner loops, one forward one backward | 32, 33, 58 |
| **Global counter** | Variable increments across all rows | 61, 63, 65, 80 |
| **Conditional character** | `if/else` decides what to print at `(i, j)` | 28, 30, 41, 48 |

### Step 6 — The Centered Pyramid Formula (memorise this!)

This solves patterns 21–24, 31–35, 81, 83, 84 and more:

```text
Spaces before content  = n - i
Stars or content       = 2*i - 1   (for odd-width pyramid)
```

Once you know this formula, **half of Level 2 becomes easy**.

### Step 7 — Code it skeleton-first

Always write the skeleton before filling in content:

```python
n = 7
for i in range(1, n+1):       # outer loop → rows
    for j in range(...):       # inner loop 1 → spaces
        print(" ", end="")
    for j in range(...):       # inner loop 2 → content
        print("*", end="")
    print()                    # move to next line
```

Fill in the `range()` values last, after you've figured out the logic from your table.

### Step 8 — Debug with n = 3

If your output looks wrong, **always test with n = 3 first**. Smaller output = easier to spot where the loop is going wrong.

## 🔑 Golden Rules to Remember

- Every pattern is just **nested loops + a print condition**
- If you see **spaces**, there's a loop for them
- If you see **mirroring**, there are **two** inner loops
- If numbers keep going across rows, use a **counter variable**
- When stuck, **print i and j** to see what values you're working with

## 📈 Suggested Attack Order

| Phase | Problems to solve first |
|||
| Warm up | 1, 3, 4, 5, 6 |
| Learn spaces | 7, 9, 21, 22 |
| Learn hollow | 25, 27, 44 |
| Learn mirroring | 32, 33, 58 |
| Learn counters | 61, 63, 65 |
| Go advanced | 81, 83, 88 |
