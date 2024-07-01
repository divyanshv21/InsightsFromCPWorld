### Cool Printing Trick in C++

This loop prints elements of an array with a space between each element and a newline after the last element:

```cpp
for (int i = 0; i < n; i++) {
    std::cout << x[i] << " \n"[i == n - 1];
}

### Explanation

- **Loop**: Iterates through each element of the array `x` of size `n`.
- **Printing**:
  - `x[i]`: Prints the `i`-th element of the array.
  - `" \n"[i == n - 1]`: Selects the character to print after the element:
    - `" \n"`: A string literal containing a space and a newline character.
    - `[i == n - 1]`: Indexes into the string `" \n"`.
      - If `i == n - 1` (true for the last element), it accesses the newline character `'\n'`.
      - Otherwise, it accesses the space character `' '`.