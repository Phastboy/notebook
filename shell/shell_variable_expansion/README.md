# Shell Variable Expansion

Variable expansion allows you to access and manipulate variables in various ways, making your scripts more versatile.

## 1. Basic Expansion

- Access the value of a variable with the variable name preceded by a dollar sign.

   **Example:**
   ```bash
   my_variable="Hello, World!"
   echo $my_variable
   ```
## 2. Brace Expansion

- Enclose the variable name in curly braces to explicitly delimit it, e.g., `${name}`.

    **Example**
    ```bash
    greeting="Hi"
    echo "${greeting}_there"

    ```

## 3. Variable Default Value

- Use `${variable:-default}` to expand the value of the variable if it's set; otherwise, use the specified default value.

    **Example**
    ```bash
    echo "${unknown_variable:-default_value}"
    ```

## 4. Variable Assignment

- Use `${variable=value}` to set a variable to a default value if it's not already set.

    **Example**
    ```bash
    echo "Before: $unset_variable"
    unset_variable="New Value" 
    echo "After: ${unset_variable=value}"
    ```

## 5. Variable Unset Check

- Use `${variable?message}` to exit the script with an error message if the variable is not set.

    **Example**
    ```bash
    echo "${existing_variable?Variable is not set.}"
    ```

## 6. Substring Expansion

- Use `${variable:offset:length}` to extract a substring from a variable.

    **Example**
    ```bash
    full_string="This is a sentence."
    echo "${full_string:5:7}"

    ```

## 7. Length Expansion

- `${#variable}` returns the length of the variable value.

    **Example**
    ```bash
    ```

## 8. Array Expansion

- `${array[@]}` expands to all elements of an array.

    **Example**
    ```bash
    ```

