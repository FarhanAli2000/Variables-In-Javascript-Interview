JavaScript Variable Declarations Example

This repository demonstrates the usage of different types of variable declarations in JavaScript, highlighting their key differences and features (var, let, and const). The code snippet includes examples of scope, redeclaration, and updates.

📝 Code Overview

The code explains:

var: Function-scoped variable that can be re-declared and updated.

let: Block-scoped variable that can be updated but not re-declared within the same scope.

const: Block-scoped variable that cannot be re-declared or updated.


🛠️ Key Features

Demonstrates the differences between var, let, and const.

Illustrates scope and behavior of JavaScript variable declarations.

Uses console.table() to print variables in a structured format.

📚 Concepts Explained

1. var

Scope: Function-scoped.

Redeclaration: Allowed.

Updating: Allowed.

2. let

Scope: Block-scoped.

Redeclaration: Not allowed in the same scope.

Updating: Allowed.

3. const

Scope: Block-scoped.

Redeclaration: Not allowed.

Updating: Not allowed.

4. undefined Value

If a variable is declared without initialization, it will have the value undefined.

5. Console Table Output

💡 Key Takeaways

Use let and const over var for better scoping and to avoid hoisting issues.

Prefer const for variables that should not be reassigned.

Use let for variables that may need to be updated.

🛠️ Technologies Used

JavaScript (ES6)

🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

👤 Author

Syed Farhan Ali

Email: tofarhanali@gmail.com
