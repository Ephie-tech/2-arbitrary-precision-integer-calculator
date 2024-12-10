# Arbitrary Precision Integer Calculator

This project implements an arbitrary-precision integer calculator in Python, without relying on native libraries for the core functionality. The calculator is wrapped in a REPL (Read-Eval-Print Loop) interface, providing a user-friendly environment to perform advanced calculations with integers of any size.

## Features

The calculator supports the following operations:

1. **Basic Arithmetic Operations**:
   - Addition (`+`)
   - Subtraction (`-`)
   - Multiplication (`*`)
   - Division (`/`)
   - Modulo (`%`)

2. **Advanced Mathematical Functions**:
   - Exponentiation (`^`)
   - Factorial (`!`)

3. **Bonus Features**:
   - Support for non-decimal bases (binary, octal, hexadecimal, etc.)
   - Fraction operations
   - Logarithms (optional)

## Usage

### Requirements
- Python 3.x installed on your system.

### Running the Calculator
1. Clone the repository or download the script.
2. Open a terminal and navigate to the script's directory.
3. Run the script using:
   ```
   python calculator.py
   ```
4. The REPL interface will start, and you can begin entering expressions.

### REPL Commands
- Enter any valid expression to calculate its result.
- Use commands like `exit` or `quit` to terminate the REPL.

### Examples

#### Basic Operations
```
> 123456789123456789 + 987654321987654321
1111111111111111110

> 10!  
3628800
```

#### Non-Decimal Base Support
```
> bin(1010) + bin(1100)
11010 (binary)

> hex(A) * hex(5)
32 (hexadecimal)
```

#### Advanced Operations
```
> 2 ^ 100
1267650600228229401496703205376

> log(1000, 10)
3.0
```

## Implementation Details
- **Core Functionality**: All arithmetic and advanced operations are implemented without reliance on Python’s built-in libraries (e.g., `math` or `decimal`).
- **Arbitrary Precision**: Custom algorithms are used to handle large integers and ensure precision.
- **Base Conversion**: Non-decimal bases are implemented using custom conversion routines.

## Future Enhancements
- Improved support for logarithms with arbitrary bases.
- Additional mathematical functions like square root, trigonometry, and gcd.
- Enhanced error handling for edge cases and invalid inputs.

## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---


