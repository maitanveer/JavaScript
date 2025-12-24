# JavaScript Task 1

## Description
This task demonstrates basic **JavaScript concepts** including:

- Variables (`const`, `let`, `var`)
- Scope
- Console output (`console.log`, `console.table`)
- Comments (`//` for single-line, `/* */` for multi-line)
- Undefined variables

The purpose is to practice the concepts discussed in class.

---

## Task Details

```javascript
console.log("Hello World");

// This is our JS Comment

const UserName = "Ali";
let UserEmail = "admin@gmail.com";
var UserPass = "50269";
Location = "Gilgit";

let PhoneNumber;

// UserName = "Basit"; // ❌ Cannot reassign const

console.log(UserName);

UserEmail = "newadmin@gmail.com";
UserPass  = "112233";
Location = "Diamer";

/*
What is Scope?
Scope defines where variables are accessible.

Why we should avoid var:
- No block scope
- Can be redeclared
- May cause bugs
*/

console.table([UserEmail, UserPass, Location]);
console.log(PhoneNumber);
