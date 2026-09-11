README Claim Audit
| README Claim                                                                  | Status                          | Evidence from `factorial.py`                                                                                |
| ----------------------------------------------------------------------------- | ------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| **Project description:** Calculates the factorial of a given number           | ✅ **Supported**                 | The code multiplies numbers from `1` to `n` and prints `Factorial of {n} = {fact}`.                         |
| **Uses a loop to calculate factorial**                                        | ✅ **Supported**                 | `for i in range(1, n + 1):` performs the repeated multiplication.                                           |
| **Beginner-friendly Python project**                                          | ✅ **Supported**                 | The code uses basic variables, a `for` loop, multiplication, and `print()`.                                 |
| **Calculates factorial of a non-negative integer**                            | ⚠️ **Not Supported**            | The code sets `n=5` directly and has no input or validation for negative/non-integer values.                |
| **Takes a number as input**                                                   | ❌ **Not Supported**             | There is no `input()` statement. The number is hard-coded as `n=5`.                                         |
| **User can enter a number**                                                   | ❌ **Not Supported**             | No user-input mechanism exists.                                                                             |
| **Calculates factorial of any given number**                                  | ⚠️ **Not Supported**            | The current code only calculates the hard-coded value `5`; changing `n` manually would be required.         |
| **Uses a `for` loop**                                                         | ✅ **Supported**                 | `for i in range(1, n + 1):` is explicitly used.                                                             |
| **No external libraries/packages are required**                               | ✅ **Supported**                 | The code imports no libraries.                                                                              |
| **Runs with Python 3.x**                                                      | ✅ **Supported**                 | The syntax `print(f"Factorial of {n} = {fact}")` is valid Python 3 syntax.                                  |
| **Command-line usage: `python factorial.py`**                                 | ✅ **Supported**                 | `factorial.py` contains a complete executable Python program with no external dependencies.                 |
| **Example: Input `5` → Output `Factorial of 5 = 120`**                        | ⚠️ **Partially Supported**      | The code has `n=5` and produces `Factorial of 5 = 120`, but `5` is **not entered as user input**.           |
| **Project structure contains `factorial.py` and `README.md`**                 | ⚠️ **Not verifiable from code** | The provided code confirms `factorial.py`, but cannot confirm whether `README.md` exists in the repository. |
| **MIT License**                                                               | ❌ **Not Supported**             | No license information appears anywhere in the provided Python code.                                        |
| **Mathematical explanation of `n!`**                                          | ✅ **Supported**                 | The multiplication logic `fact = fact * i` implements the factorial calculation.                            |
| **Project calculates factorial using a loop rather than an external library** | ✅ **Supported**                 | The calculation is explicitly performed with `for` and multiplication; no imports are used.                 |

Main audit finding

The biggest mismatch is that the README describes an interactive factorial calculator, while the actual code is a fixed factorial calculation for n = 5. There is no input() function or validation.

Also, the README's MIT License claim cannot be verified from factorial.py; it would need an actual LICENSE file or license declaration in the repository.
