# First-C-Program-Calculating-Simple-Interest
# First C Program: Calculating Simple Interest in C

Welcome to the **Simple Interest Calculator**! This program is designed to help beginners understand the basics of C programming by implementing a simple financial calculation. By writing and executing this program, you will:

- Learn the structure of a basic C program.
- Understand how to use variables, input, and output in C.
- Perform a simple mathematical operation to calculate interest.

---

## Features

- **User-Friendly Input**: Enter the principal amount, rate of interest, and time period.
- **Accurate Calculation**: The program computes simple interest using the formula:

  \[ \text{Simple Interest} = (P \times R \times T) / 100 \]
  
  Where:
  - \( P \) = Principal amount
  - \( R \) = Rate of interest (in percentage)
  - \( T \) = Time period (in years)

- **Clean Output**: Displays the calculated interest clearly.

---

## Program Overview

Here's a quick summary of the program structure:

1. **Header Files**: Includes `<stdio.h>` for input and output functionality.
2. **Variable Declaration**: Declares variables to store the principal amount, rate, time, and calculated interest.
3. **Input Section**: Prompts the user to enter the required values.
4. **Calculation**: Implements the simple interest formula.
5. **Output Section**: Displays the result to the user.

---

## How to Run the Program

1. **Prerequisites**: Ensure you have a C compiler (e.g., GCC) installed on your system.

2. **Steps**:
   - Save the program file as `simple_interest.c`.
   - Open a terminal or command prompt and navigate to the directory containing the file.
   - Compile the program using the command:
     ```
     gcc simple_interest.c -o simple_interest
     ```
   - Run the executable:
     ```
     ./simple_interest
     ```

3. **Example Execution**:
   ```
   Enter the principal amount: 1000
   Enter the rate of interest: 5
   Enter the time period in years: 2
   Simple Interest = 100.00
   ```

---

## Sample Code

```c
#include <stdio.h>

int main() {
    float principal, rate, time, interest;

    // Input principal amount, rate of interest, and time period
    printf("Enter the principal amount: ");
    scanf("%f", &principal);

    printf("Enter the rate of interest: ");
    scanf("%f", &rate);

    printf("Enter the time period in years: ");
    scanf("%f", &time);

    // Calculate simple interest
    interest = (principal * rate * time) / 100;

    // Output the result
    printf("Simple Interest = %.2f\n", interest);

    return 0;
}
```

---

## Learning Outcomes

By completing this program, you will:

- Understand the basics of reading input and displaying output in C.
- Learn how to use arithmetic operators in C.
- Gain confidence in writing and executing your first C program.

---

## Next Steps

Once you've successfully run this program, challenge yourself with the following:

- Modify the program to accept time in months and convert it to years.
- Enhance the program to calculate compound interest.
- Add error handling for invalid inputs.

---

Happy Coding! 😊
