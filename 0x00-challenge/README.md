# Fixed source code.

## Tasks:

+ Task 0. **FizzBuzz**
  * To print `FizzBuzz` instead of `Fizz` at the number `15`.
    * Compare the fixed source code in this directory with the one in the root dir
    * File: `0-fizzbuzz.py`

+ Task 1. **Print square**
  * The error was in line `17` it should be:
    ```javascript
    size = parseInt(process.argv[2])
    ```
  * Look at the original source code in the root directory.
  * File: `1-print_square.js`

+ Task 2. **Sort**
  * Fix sort integer arguments in ascending order.
    * The original source code is in root directory and the error was in line `23`.
    * The problem is we should insert integer in his right position by doing this:
      ```ruby
      result.insert(i, i_arg)
      
      # And add this at the last end keyword and befor puts result
      result.sort!
      ```

