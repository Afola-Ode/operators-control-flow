##### 1a. Arithmetic Operators:

- Addition: +
- Subtraction: -
- Multiplication: \*
- Division: /
- Remainder (modulus): %
- Increment: ++
- Decrement: --

##### 1b. Assignment Operators:

- Assignment: =
- Addition assignment: +=
- Subtraction assignment: -=
- Multiplication assignment: \*=
- Division assignment: /=
- Remainder (modulus) assignment: %=
- Left shift assignment: <<=
- Right shift assignment: >>=
- Unsigned right shift assignment: >>>=
- Bitwise AND assignment: &=
- Bitwise OR assignment: |=
- Bitwise XOR assignment: ^=

##### 1c. Comparison Operators:

- Equal to: ==
- Not equal to: !=
- Strict equal to: ===
- Strict not equal to: !==
- Greater than: >
- Greater than or equal to: >=
- Less than: <
- Less than or equal to: <=

##### 1d. Logical Operators:

- Logical AND: &&
- Logical OR: ||
- Logical NOT: !

##### 1e. Bitwise Operators:

- Bitwise AND: &
- Bitwise OR: |
- Bitwise XOR: ^
- Bitwise NOT: ~
- Left shift: <<
- Right shift: >>
- Unsigned right shift: >>>

2.

- Addition (+):
  `let sum = 5 + 7; `// sum is now 12
  `let result = "Hello " + "world!";` // result is now "Hello world!"

- Subtraction (-):
  `let difference = 10 - 3;` // difference is now 7
  `let negative = -5;` // negative is now -5

- Multiplication (\*):
  `let quotient = 25 / 5;` // quotient is now 5
  `let decimal = 7 / 2;` // decimal is now 3.5

- Remainder (modulus) (%):
  `let remainder = 17 % 3;` // remainder is now 2
  `let even = 16 % 2;` // even is now 0

- Increment (++):
  `let count = 0;`
  `count++;` // count is now 1
  `let value = 5;`
  `let result = value++;` // result is 5, value is now 6

- Decrement (--):
  `let count = 10;`
  `count--;` // count is now 9
  `let value = 5;`
  `let result = value--; `// result is 5, value is now 4

- Assignment Operators:
  `let x = 5;` // x is now 5
  `let y = "Hello";` // y is now "Hello"

- Addition assignment (+=):
  `let sum = 5;`
  `sum += 7; `// sum is now 12
  `let message = "Hello";`
  `message += " world!";` // message is now "Hello world!"

- Subtraction assignment (-=):
  `let difference = 10;`
  `difference -= 3;` // difference is now 7
  `let value = 5;`
  `value -= 2;` // value is now 3

- Multiplication assignment (_=):
  `let product = 4;`
  `product _= 6;`// product is now 24`let value = 5;`
`value \*= 2; `// value is now 10

- Division assignment (/=):
  `let quotient = 25;`
  `quotient /= 5;` // quotient is now 5
  `let value = 10;`
  `value /= 3;` // value is now 3.3333...

- Remainder (modulus) assignment (%=):
  `let remainder = 17;`
  `remainder %= 3;` // remainder is now 2
  `let value = 10;`
  `value %= 3;` // value is now 1

- Left shift assignment (<<=):
  `let x = 5;` // x is 101 in binary
  `x <<= 2;` // x is now 10100 in binary, which is 20 in decimal
  `let y = 7;` // y is 111 in binary
  `y <<= 3;` // y is now 111000 in binary, which is 56 in decimal

- Right shift assignment (>>=):
  `let x = 16`; // x is 10000 in binary
  `x >>= 2;` // x is now 100 in binary, which is 4 in decimal
  `let y = 20;` // y is 10100 in binary
  `y >>= 3;` // y is now 10 in binary, which is 2 in`

#### 3.

`let classGroup = "Arts";` // Change this to Bolatito's actual class group

`if (classGroup === "Science") {
  console.log("Your science subjects are: Physics, Chemistry, Biology, Technical Drawing");
} else if (classGroup === "Social Science") {
  console.log("Your social science subjects are: Accounting, Commerce, Marketing, Geography");
} else if (classGroup === "Arts") {
  console.log("Your arts subjects are: Government, Economics, Literature, History");
} else {
  console.log("Invalid class group. Your general subjects are: English, Mathematics");
}`

#### 4.

1
8
15

#### 5.

function findnearestPwr(num){
let pwr;
for(let i =1; i<num; i\*\*2){
pwr = i;
}
}

console.log(`The number ${pwr} is the power of 2 nearest to ${num}.`)
