# JavaScript Basics

Answer following questions in this file.

## What is JavaScript?

```
is a programming language used to make websites interactive and dynamic. Developers can make animations, click-responsive buttons, and make the site "react" to what the user does.```

## About values

### What is a primitive value?

```
A primitive value is a basic data type in JavaScript. It is like a simple block of information, such as a number or a word, that cannot be changed.
```

### Which are primitive values? Explain them with at least one example for primitive.

```
Primitive values ​​in JavaScript are:

1. Number: Any number, either integer or decimal. Example: `42` or `3.14`
2. String: Any group of letters or text. Example: `"Hello, World"`
3. Boolean: Can only be `true` or `false`. Example: `true`
4. Null: Something that has no value. It's like saying “there's nothing here”. Example: `null`
5. Undefined: When we declare a variable but don't give it a value, it's `undefined`. Example: `let x; // x is undefined`
6. Symbol: A unique value used to identify things. Example: `Symbol("id")`
7. BigInt: Super-large numbers, larger than normal numbers. Example: `BigInt(9007199254740991)`

These values ​​are "basic" and cannot be changed.
```

## About variables

### What is a variable in JS?

```
A variable is like a box where we store information for later use. It is a way to remember things in the program.
```

### How many ways can we define a variable in JS? Is there any not recommended way?

```
There are three ways to define a variable:

1. var: This is the old way of declaring variables and is not recommended much because it can cause errors.
2. let: This is used to declare variables that can change. It is safer and more modern than `var`.
3. const: This is used when we want the value of the variable to never change.
```

### Which are the most used var naming conventions in JS?

```
1. camelCase: It starts with a lowercase letter and each new word is capitalized. Example: `fullName`
2. PascalCase: All words start with a capital letter, and it is used mostly for class names. Example: `fullName`
3. snake_case: It is not used much in JavaScript, but it is sometimes seen in constant names. Example: `MAX_VALUE`
```

## About operators

### Which are the main comparison operators in JS? Explain them with at least one example for primitive.

```
Comparison operators help us compare values. Some of the most common ones are:

1. == (equal): Compares whether two values ​​are equal, even if they are of different types. Example: `5 == '5'` is `true`
2. === (strictly equal)**: Compares whether two values ​​are equal and of the same type. Example: `5 === '5'` is `false`
3. != (not equal): Compares whether two values ​​are not equal, even if they are of different types. Example: `5 != '6'` is `true`
4. !== (strictly not equal): Compares whether two values ​​are not equal or do not have the same type. Example: `5 !== '5'` is `true`
5. > (greater than): Sees whether the value on the left is greater than the value on the right. Example: `10 > 5` is `true`
6. < (less than): See if the value on the left is less than the value on the right. Example: `5 < 10` is `true`
7. >= (greater than or equal): See if the value on the left is greater than or equal to the value on the right. Example: `10 >= 10` is `true`
8. <= (less than or equal): See if the value on the left is less than or equal to the value on the right. Example: `5 <= 10` is `true`
```

### Which are the main logical operators in JS? Explain them with at least one example for primitive.

```
Logical operators allow us to combine conditions. The most common ones are:

1. && (AND): Only `true` if both conditions are `true`. Example: `(5 > 3) && (3 < 10)` is `true`
2. || (OR): It is `true` if at least one of the two conditions is `true`. Example: `(5 < 3) || (3 < 10)` is `true`
3. ! (NOT): Changes the value of the condition to its opposite. Example: `!(5 > 3)` is `false`
```
