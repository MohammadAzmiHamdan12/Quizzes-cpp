# 📝 C++ Final Exam Review

مجموعة من الأسئلة لمراجعة أساسيات لغة C++، مصممة لتكون واضحة وسهلة القراءة على جميع الأجهزة.

---

## 🧠 Part 1: Theoretical & Fill-in-the-Blank

<details>
  <summary><strong>Q1: Which header file is required for input and output operations in C++?</strong></summary>
  
  - [ ] `math.h`
  - [x] `iostream`
  - [ ] `string`
  - [ ] `stdio.h`
</details>

<details>
  <summary><strong>Q2: Which of the following is a reserved word in C++?</strong></summary>
  
  - [ ] `myVariable`
  - [x] `while`
  - [ ] `number1`
  - [ ] `getInput`
</details>

<details>
  <summary><strong>Q5: Fill the missing code to declare a pointer to integer named 'ptr'.</strong></summary>
  
  ```cpp
  ____ ptr;
  ```
  - [ ] `int &ptr;`
  - [x] `int *ptr;`
  - [ ] `pointer int ptr;`
  - [ ] `int ptr;`
</details>

<details>
  <summary><strong>Q7: Which operator is used for conditional (ternary) operation?</strong></summary>
  
  - [ ] `:`
  - [x] `?:`
  - [ ] `++`
  - [ ] `==`
</details>

<details>
  <summary><strong>Q9: Which function reads a line from input including spaces?</strong></summary>
  
  - [ ] `cin`
  - [x] `getline`
  - [ ] `get`
  - [ ] `cout`
</details>

<details>
  <summary><strong>Q12: Which is the correct way to declare a float variable?</strong></summary>
  
  - [ ] `float x = 1;`
  - [x] `float x = 1.0;`
  - [ ] `float x = '1';`
  - [ ] `float x = "1";`
</details>

<details>
  <summary><strong>Q14: Complete the code to define a function that returns int.</strong></summary>
  
  ```cpp
  ____ myFunction() {
      return 5;
  }
  ```
  - [x] `int`
  - [ ] `void`
  - [ ] `float`
  - [ ] `double`
</details>

<details>
  <summary><strong>Q16: Which of these is correct for dynamic memory allocation of an int?</strong></summary>
  
  - [x] `int *p = new int;`
  - [ ] `int p = new int;`
  - [ ] `int *p = int();`
  - [ ] `pointer int p = new int;`
</details>

<details>
  <summary><strong>Q18: Which is correct way to declare a one-dimensional array of size 5?</strong></summary>
  
  - [x] `int arr[5];`
  - [ ] `int arr(5);`
  - [ ] `array arr[5];`
  - [ ] `int arr{};`
</details>

<details>
  <summary><strong>Q20: Complete the code to read input from user into variable 'num'.</strong></summary>
  
  ```cpp
  ____ num;
  ```
  - [x] `cin >>`
  - [ ] `cout <<`
  - [ ] `scanf()`
  - [ ] `get()`
</details>

<details>
  <summary><strong>Q22: Which of these is correct for defining a constant in C++?</strong></summary>
  
  - [x] `const int x = 10;`
  - [ ] `int const x;`
  - [ ] `int x = constant 10;`
  - [ ] `define x = 10;`
</details>

<details>
  <summary><strong>Q24: Which operator is used for accessing members of a structure through a pointer?</strong></summary>
  
  - [x] `->`
  - [ ] `.`
  - [ ] `*`
  - [ ] `#`
</details>

<details>
  <summary><strong>Q26: Complete the for loop header.</strong></summary>
  
  ```cpp
  for(____) {
      cout << i;
  }
  ```
  - [x] `int i=0; i<5; i++`
  - [ ] `i=0; i<5; i++`
  - [ ] `int i<5; i++`
  - [ ] `for i=0 to 5`
</details>

<details>
  <summary><strong>Q28: Which function frees dynamically allocated memory?</strong></summary>
  
  - [x] `delete`
  - [ ] `free()`
  - [ ] `clear()`
  - [ ] `deallocate()`
</details>

<details>
  <summary><strong>Q30: Complete the code to open a file for writing.</strong></summary>
  
  ```cpp
  ofstream file;
  file.____("data.txt");
  ```
  - [x] `open`
  - [ ] `read`
  - [ ] `write`
  - [ ] `getline`
</details>

<details>
  <summary><strong>Q32: Which of the following is correct for declaring a double variable?</strong></summary>
  
  - [x] `double num = 3.14;`
  - [ ] `double num = '3.14';`
  - [ ] `double num = 3;`
  - [ ] `int num = 3.14;`
</details>

<details>
  <summary><strong>Q34: Complete the code to read a character from user.</strong></summary>
  
  ```cpp
  char ch;
  ____ >> ch;
  ```
  - [x] `cin`
  - [ ] `cout`
  - [ ] `getline`
  - [ ] `scanf()`
</details>

<details>
  <summary><strong>Q36: Which of the following is correct for a two-dimensional array of 2x3?</strong></summary>
  
  - [x] `int arr[2][3];`
  - [ ] `int arr[3][2];`
  - [ ] `int arr[2,3];`
  - [ ] `array arr[2][3];`
</details>

<details>
  <summary><strong>Q38: Which keyword defines a variable that keeps its value between function calls?</strong></summary>
  
  - [x] `static`
  - [ ] `local`
  - [ ] `global`
  - [ ] `dynamic`
</details>

<details>
  <summary><strong>Q40: Complete the code to define a function that returns nothing.</strong></summary>
  
  ```cpp
  ____ myFunction() {
      cout << "Hello";
  }
  ```
  - [x] `void`
  - [ ] `int`
  - [ ] `double`
  - [ ] `float`
</details>

<details>
  <summary><strong>Q42: Which of these operators is used for incrementing a value by 1?</strong></summary>
  
  - [x] `++`
  - [ ] `--`
  - [ ] `+=`
  - [ ] `=+`
</details>

<details>
  <summary><strong>Q44: Which stream is used to write data to a file?</strong></summary>
  
  - [x] `ofstream`
  - [ ] `ifstream`
  - [ ] `cin`
  - [ ] `cout`
</details>

<details>
  <summary><strong>Q46: Complete code to include iomanip header.</strong></summary>
  
  ```cpp
  ____
  ```
  - [x] `#include <iomanip>`
  - [ ] `#include <iomanip.h>`
  - [ ] `#include <iostream>`
  - [ ] `#include <math.h>`
</details>

<details>
  <summary><strong>Q48: Which of the following is correct to declare an enum?</strong></summary>
  
  - [x] `enum Color {Red, Green, Blue};`
  - [ ] `enum Color = {Red, Green, Blue};`
  - [ ] `enum Color();`
  - [ ] `enum Color[] = {Red, Green, Blue};`
</details>

<details>
  <summary><strong>Q50: Complete code to deallocate dynamic memory.</strong></summary>
  
  ```cpp
  int *ptr = new int;
  ____ ptr;
  ```
  - [x] `delete`
  - [ ] `free`
  - [ ] `clear`
  - [ ] `remove`
</details>

<details>
  <summary><strong>Q52: Which is correct way to declare a pointer to double?</strong></summary>
  
  - [x] `double *ptr;`
  - [ ] `double &ptr;`
  - [ ] `pointer double ptr;`
  - [ ] `double ptr;`
</details>

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
