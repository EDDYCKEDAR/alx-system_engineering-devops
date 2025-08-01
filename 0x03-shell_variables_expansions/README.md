# 0x03. Shell, init files, variables and expansions

## Description

This project focuses on advanced shell scripting concepts including:

- Shell initialization files and variable scope
- Creating aliases
- Local vs global variables
- Arithmetic and string operations
- Environment variable manipulation
- Command substitution and path management

---

## Tasks Summary

### 0. `<o>`
- **Script:** `0-alias`
- Creates an alias `ls` that runs `rm *` (dangerous—removes all files in current dir).

### 1. `Hello you`
- **Script:** `1-hello_you`
- Prints `hello user`, where `user` is the current Linux username.

### 2. `The path to success is to take massive, determined action`
- **Script:** `2-path`
- Adds `/action` to the end of the `PATH`.

### 3. `If the path be beautiful, let us not ask where it leads`
- **Script:** `3-paths`
- Counts the number of directories in the `PATH`.

### 4. `Global variables`
- **Script:** `4-global_variables`
- Lists all environment variables.

### 5. `Local variables`
- **Script:** `5-local_variables`
- Lists local variables, environment variables, and functions.

### 6. `Local variable`
- **Script:** `6-create_local_variable`
- Creates a local variable `BEST=School`.

### 7. `Global variable`
- **Script:** `7-create_global_variable`
- Creates a global variable `BEST=School`.

### 8. `Every addition to true knowledge is an addition to human power`
- **Script:** `8-true_knowledge`
- Adds `128` to the value of `TRUEKNOWLEDGE` and prints the result.

### 9. `Divide and rule`
- **Script:** `9-divide_and_rule`
- Prints result of `POWER` divided by `DIVIDE`.

### 10. `Love is anterior to life...`
- **Script:** `10-love_exponent_breath`
- Displays `BREATH` to the power of `LOVE`.

### 11. `There are 10 types of people...`
- **Script:** `11-binary_to_decimal`
- Converts binary number in `BINARY` env var to decimal.

### 12. `Combination`
- **Script:** `12-combinations`
- Prints all combinations of two lowercase letters except `oo`, one per line.

### 13. `Floats`
- **Script:** `13-print_float`
- Prints `NUM` with 2 decimal places.

---

## Advanced Tasks

### 14. `Decimal to Hexadecimal`
- **Script:** `100-decimal_to_hexadecimal`
- Converts decimal number in `DECIMAL` env var to hexadecimal.

### 15. `ROT13`
- **Script:** `101-rot13`
- Encodes/decodes text using ROT13 cipher.

### 16. `Odd lines only`
- **Script:** `102-odd`
- Prints every other line from input, starting with the first.

### 17. `Water and Stir`
- **Script:** `103-water_and_stir`
- Adds WATER and STIR (custom base), prints result in base bestchol.

---

## How to Use

Make each script executable:

```bash
chmod +x <script_name>
