Here's how you can format the content into a `README.md` file for a Git repository:

```markdown
# Swift Programming Exercises

## Data-type Exercises

### Exercise 1: Working with Integers
**Task**: Create an integer variable for age and assign your age to it. Then, increase it by 1.
- Use `var` and `Int`.

### Exercise 2: Floating-Point Numbers
**Task**: Declare a constant that stores the value of pi (π) as a double with up to 5 decimal places.
- Use `let` and `Double`.

### Exercise 3: Strings
**Task**: Concatenate two strings to form a sentence.
- Example: `"Hello, "` and `"world!"`.

### Exercise 4: Boolean Logic
**Task**: Create a boolean variable to store a true/false value and print a statement based on its value.
- Use `Bool` and an `if` statement.

### Exercise 5: Type Inference
**Task**: Declare a variable with a value and let Swift infer its type.
- Assign `"Hello, Swift!"` and see how Swift infers it as a `String`.

### Exercise 6: Tuples
**Task**: Create a tuple representing a HTTP status code, containing a number (e.g., 404) and a description (e.g., "Not Found").
- Use tuple like `(404, "Not Found")`.

### Exercise 7: Arrays
**Task**: Create an array of your three favorite fruits and add another fruit to it.
- Use `var`, `Array<String>`, and array methods.

### Exercise 8: Dictionaries
**Task**: Make a dictionary with keys as country names and values as their capitals. Add a new country-capital pair to it.
- Use `var`, `Dictionary<String, String>`.

### Exercise 9: Optionals
**Task**: Create an optional string and use optional binding to unwrap it.
- Use `var`, `String?`, and `if let`.

### Exercise 10: Enums
**Task**: Define an enum for days of the week and create a variable holding a day.
- Use `enum` and set it to `.monday` or any other day.

### Bonus Exercise: Working with Characters
**Task**: Loop through a string and print each character.
- Use `for-in` loop and `String`.

## Operators Exercises

### Exercise 1: Arithmetic Operators
**Task**: Create variables representing a wallet with $150, a purchase costing $20.50, and calculate the remaining balance.
- Use the subtraction operator `-`.

### Exercise 2: Compound Assignment Operators
**Task**: You have a score variable initially set to zero. Add 10 to it using a compound assignment operator.
- Use the `+=` operator.

### Exercise 3: Comparison Operators
**Task**: Determine if two strings are equal and if one integer is greater than another.
- Use `==` for string comparison, and `>` for integer comparison.

### Exercise 4: Logical Operators
**Task**: Check if two conditions are both true - if a number is greater than 10 and less than 20.
- Use the logical AND operator `&&`.

### Exercise 5: Ternary Conditional Operator
**Task**: Use the ternary operator to check if a number is even and assign the result to a String variable ("even" or "odd").
- Hint: `let result = (number % 2 == 0) ? "even" : "odd"`

###

### Exercise 6: Range Operators
**Task**: Use a range operator to loop through numbers 1 to 10 and print them.
- Use the `for-in` loop with a closed range operator `...`.

### Exercise 7: Nil-Coalescing Operator
**Task**: Create an optional variable and use the nil-coalescing operator to assign a default value.
- `let name: String? = nil; let defaultName = name ?? "Guest"`

### Exercise 8: Unary Operators
**Task**: Use the unary minus operator to change a positive number to negative and vice versa.
- `let positive = 5; let negative = -positive; let turnPositive = -negative`

### Exercise 9: Overflow Operators
**Task**: Try adding two maximum values of `UInt8` using an overflow operator.
- `let max = UInt8.max; let overflowed = max &+ max`

### Exercise 10: Identity Operators
**Task**: Create two class instances and check if they are the same instance using the identity operator.
- `class MyClass {}; let object1 = MyClass(); let object2 = MyClass(); let isSame = object1 === object2`

---

These exercises cover the basic data types and operators in Swift, providing a hands-on approach to understanding their use in various scenarios. Practice these in a Swift playground for an optimal learning experience.
