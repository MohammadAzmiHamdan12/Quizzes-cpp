# 📝 C++ Final Exam Review

مجموعة من الأسئلة لمراجعة أساسيات لغة C++، مصممة لتكون واضحة وسهلة القراءة على جميع الأجهزة.

---

## 🧠 Part 1: Theoretical Questions

| # | السؤال | الخيارات |
| :-- | :--- | :--- |
| **Q1** | Which header file is required for input and output operations in C++? | `iostream` |
| **Q2** | Which of the following is a reserved word in C++? | `while` |
| **Q5** | Fill the missing code to declare a pointer to integer named 'ptr': `____ ptr;` | `int *ptr;` |
| **Q7** | Which operator is used for conditional (ternary) operation? | `?:` |
| **Q9** | Which function reads a line from input including spaces? | `getline` |
| **Q12**| Which is the correct way to declare a float variable? | `float x = 1.0;` |
| **Q14**| Complete the code to define a function that returns int: `____ myFunction() { return 5; }` | `int` |
| **Q16**| Which of these is correct for dynamic memory allocation of an int? | `int *p = new int;` |
| **Q18**| Which is correct way to declare a one-dimensional array of size 5? | `int arr[5];` |
| **Q20**| Complete the code to read input from user into variable 'num': `____ num;` | `cin >>` |
| **Q22**| Which of these is correct for defining a constant in C++? | `const int x = 10;` |
| **Q24**| Which operator is used for accessing members of a structure through a pointer? | `->` |
| **Q26**| Complete the for loop header: `for(____) { ... }` | `int i=0; i<5; i++` |
| **Q28**| Which function frees dynamically allocated memory? | `delete` |
| **Q30**| Complete the code to open a file for writing: `ofstream file; file.____("data.txt");` | `open` |
| **Q32**| Which of the following is correct for declaring a double variable? | `double num = 3.14;` |
| **Q34**| Complete the code to read a character from user: `char ch; ____ >> ch;` | `cin` |
| **Q36**| Which of the following is correct for a two-dimensional array of 2x3? | `int arr[2][3];` |
| **Q38**| Which keyword defines a variable that keeps its value between function calls? | `static` |
| **Q40**| Complete the code to define a function that returns nothing: `____ myFunction() { ... }` | `void` |
| **Q42**| Which of these operators is used for incrementing a value by 1? | `++` |
| **Q44**| Which stream is used to write data to a file? | `ofstream` |
| **Q46**| Complete code to include iomanip header: `____` | `#include <iomanip>` |
| **Q48**| Which of the following is correct to declare an enum? | `enum Color {Red, Green, Blue};` |
| **Q50**| Complete code to deallocate dynamic memory: `int *ptr = new int; ____ ptr;` | `delete` |
| **Q52**| Which is correct way to declare a pointer to double? | `double *ptr;` |

---

## 💻 Part 2: Code Output Prediction

<details>
  <summary><strong>Q3: What is the output?</strong></summary>

  ```cpp
  int x = 5;
  x += 3;
  cout << x;
  ```
  **Answer:** `8`
</details>

<details>
  <summary><strong>Q4: What is the value of 'y'?</strong></summary>

  ```cpp
  int y = 10;
  y--;
  ```
  **Answer:** `9`
</details>

<details>
  <summary><strong>Q6: What will be printed?</strong></summary>

  ```cpp
  int a = 7;
  int b = 2;
  cout << a / b;
  ```
  **Answer:** `3` (Integer division)
</details>

<details>
  <summary><strong>Q8: Predict the output:</strong></summary>

  ```cpp
  int n = 5;
  cout << ++n;
  ```
  **Answer:** `6`
</details>

<details>
  <summary><strong>Q10: Output of the code:</strong></summary>

  ```cpp
  char ch = 'A';
  ch += 2;
  cout << ch;
  ```
  **Answer:** `C`
</details>

<details>
  <summary><strong>Q11: What is the output?</strong></summary>

  ```cpp
  int x = 3, y = 4;
  cout << x * y;
  ```
  **Answer:** `12`
</details>

<details>
  <summary><strong>Q13: Output of the following code?</strong></summary>

  ```cpp
  int a = 5;
  int b = 10;
  cout << (a > b ? a : b);
  ```
  **Answer:** `10`
</details>

<details>
  <summary><strong>Q15: Predict output:</strong></summary>

  ```cpp
  int n = 0;
  for(int i = 0; i < 3; i++) {
      n += i; // 0 + 1 + 2
  }
  cout << n;
  ```
  **Answer:** `3`
</details>

<details>
  <summary><strong>Q17: Output of the code?</strong></summary>

  ```cpp
  int x = 7;
  x %= 3;
  cout << x;
  ```
  **Answer:** `1`
</details>

<details>
  <summary><strong>Q19: What will be printed?</strong></summary>

  ```cpp
  int x = 2;
  int y = ++x + 5; // x becomes 3, then y = 3 + 5
  cout << y;
  ```
  **Answer:** `8`
</details>

<details>
  <summary><strong>Q21: Output of this code?</strong></summary>

  ```cpp
  char ch = 'B';
  ch--;
  cout << ch;
  ```
  **Answer:** `A`
</details>

<details>
  <summary><strong>Q23: Output of the code?</strong></summary>

  ```cpp
  int x = 3;
  int y = x++; // y gets the original value of x (3), then x becomes 4
  cout << y;
  ```
  **Answer:** `3`
</details>

<details>
  <summary><strong>Q25: Predict output:</strong></summary>

  ```cpp
  int a = 1;
  while(a < 4) {
      cout << a;
      a++;
  }
  ```
  **Answer:** `123`
</details>

<details>
  <summary><strong>Q27: Output?</strong></summary>

  ```cpp
  int arr = {1, 2, 3};
  cout << arr;
  ```
  **Answer:** `2`
</details>

<details>
  <summary><strong>Q29: Output?</strong></summary>

  ```cpp
  int x = 2;
  int y = 3;
  cout << x << y;
  ```
  **Answer:** `23`
</details>

<details>
  <summary><strong>Q31: Output of the code?</strong></summary>

  ```cpp
  int x = 4;
  int y = 5;
  cout << x + y * 2; // 4 + 10
  ```
  **Answer:** `14`
</details>

<details>
  <summary><strong>Q33: Output?</strong></summary>

  ```cpp
  int a = 1;
  a += 5;
  cout << a;
  ```
  **Answer:** `6`
</details>

<details>
  <summary><strong>Q35: Output of the code?</strong></summary>

  ```cpp
  int x = 10;
  cout << x / 4;
  ```
  **Answer:** `2` (Integer division)
</details>

<details>
  <summary><strong>Q37: Predict output:</strong></summary>

  ```cpp
  int x = 2;
  int y = 3;
  cout << x * y + 1; // 6 + 1
  ```
  **Answer:** `7`
</details>

<details>
  <summary><strong>Q39: Output of the code?</strong></summary>

  ```cpp
  int a = 3, b = 4;
  cout << (a && b); // Both are non-zero, so true (1)
  ```
  **Answer:** `1`
</details>

<details>
  <summary><strong>Q41: Output?</strong></summary>

  ```cpp
  int x = 5;
  cout << x-- + 2; // 5 + 2 is printed, then x becomes 4
  ```
  **Answer:** `7`
</details>

<details>
  <summary><strong>Q43: Output of the code?</strong></summary>

  ```cpp
  int x = 3;
  int y = 2;
  cout << x % y;
  ```
  **Answer:** `1`
</details>

<details>
  <summary><strong>Q45: Predict output:</strong></summary>

  ```cpp
  int x = 1;
  do {
      cout << x;
      x++;
  } while(x < 4);
  ```
  **Answer:** `123`
</details>

<details>
  <summary><strong>Q47: Output?</strong></summary>

  ```cpp
  #include <iomanip> // Required for setprecision
  // ...
  double x = 3.567;
  cout << fixed << setprecision(2) << x;
  ```
  **Answer:** `3.57`
</details>

<details>
  <summary><strong>Q49: Output?</strong></summary>

  ```cpp
  int arr = {1, 2, 3};
  cout << arr + arr; // 1 + 3
  ```
  **Answer:** `4`
</details>

<details>
  <summary><strong>Q51: Output of the code?</strong></summary>

  ```cpp
  int x = 5;
  int y = 2;
  cout << x % y;
  ```
  **Answer:** `1`
</details>

<details>
  <summary><strong>Q53: Output?</strong></summary>

  ```cpp
  int a = 3, b = 4;
  cout << a << b;
  ```
  **Answer:** `34`
</details>
