
# 🧮 C++ Calculator

This repository contains a simple command-line calculator written in C++. The calculator can perform a variety of basic arithmetic operations, trigonometric functions, logarithmic calculations, and more.

## 📋 Features

- **Basic Arithmetic Operations**: Addition, multiplication, division.
- **Advanced Mathematical Functions**: Power, root extraction, logarithms.
- **Trigonometric Functions**: Sine, cosine, tangent, cotangent.
- **Rounding Function**: Rounds a given number to the nearest integer.
- **Information Menu**: Provides details about the calculator version and the developer.

## 🚀 Getting Started

### Prerequisites

- A C++ compiler (e.g., GCC, Clang).
- Basic knowledge of how to compile and run C++ programs.

### 🛠️ Compilation and Running

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Antot-12/Calculator_cpp.git
    cd Calculator_cpp
    ```

2. **Compile the code**:
    ```bash
    g++ -o calculator calculator.cpp
    ```

3. **Run the compiled program**:
    ```bash
    ./calculator
    ```

### 📋 How to Use

Once you run the program, you will be presented with a menu of options. You can select the desired operation by entering the corresponding number.

Example:

```bash
Яку дію ви хочете зробити?

1. Сума чисел
2. Добуток чисел
3. Поділити числа
4. Піднести до степеня
5. Добути корінь
6. Обрахувати логарифм
7. Обрахувати синус
8. Обрахувати косинус
9. Обрахувати тангенс
10. Обрахувати котангенс
11. Округлити число
12. Про калькулятор
13. Вийти
> 1
```

### 📄 Example Operations

- **Addition**:
  - Select option `1`.
  - Enter the two numbers when prompted.
  - The program will display the sum of the two numbers.

- **Power Calculation**:
  - Select option `4`.
  - Enter the base and the exponent when prompted.
  - The program will display the result of raising the base to the power of the exponent.

- **Logarithm**:
  - Select option `6`.
  - Enter the number and the logarithm base when prompted.
  - The program will display the logarithm of the number with the specified base.

- **Trigonometric Functions**:
  - Options `7`, `8`, `9`, and `10` allow you to calculate the sine, cosine, tangent, and cotangent of an angle (in degrees), respectively.

### 🛠️ Developer Information

You can view information about the calculator and its developer by selecting option `12` in the menu. This will display details such as the version number and the developer's name.

### 🛠 Troubleshooting

- **Invalid Input**: If you enter an incorrect option number, the program will prompt you to enter a valid number.
- **Division by Zero**: Make sure to avoid division by zero in the division operation, as this can cause errors.

---

Enjoy using the C++ calculator! 🧮
