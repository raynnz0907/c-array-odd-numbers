# c-array-odd-numbers
A simple C program that counts how many odd numbers exist inside an integer array. Demonstrates array handling, loops, modular arithmetic, and function usage in C.

# Count Odd Numbers in an Array (C Program)

This repository contains a simple and clean C program that counts how many **odd numbers** are present in an integer array. It demonstrates basic concepts like arrays, loops, functions, and modular arithmetic in C.

---

## 🚀 Features
- Counts odd numbers in an array  
- Uses a separate function for cleaner code  
- Beginner-friendly  
- No external libraries required  

---

## 🧠 How It Works
The program loops through each element of the array and checks:

```
if (arr[i] % 2 != 0)
```

If true → it increases the counter.  
Finally, it returns the **total count of odd numbers**.

---

## 📌 Code

```c
#include <stdio.h>

int oddNums(int arr[], int n);

int main(){
    int arr[] = {1,2,3,4,5,6};
    printf("%d", oddNums(arr,6));   
    return 0;
}

int oddNums(int arr[], int n){
    int count = 0;

    for(int i=0; i<n; i++){
        if(arr[i] % 2 != 0){
            count++;
        }
    }

    return count;
}
```

---

## ▶️ Output

For the array:  
`{1, 2, 3, 4, 5, 6}`

The program prints:

```
3
```

Because the odd numbers are: **1, 3, 5**

---

## 🛠️ How to Run

1. Clone the repository:
   ```
   git clone <your-repo-link>
   ```

2. Compile:
   ```
   gcc odd.c -o odd
   ```

3. Run:
   ```
   ./odd
   ```

---

## 📚 Concepts Used
- Arrays  
- Functions  
- For loops  
- If conditions  
- Modulo operator  

---

## ⭐ Support
If you found this helpful, consider starring ⭐ the repo!

