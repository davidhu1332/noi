



## 运算符优先级速查表


### C++ operator precedence and associativity table

The following table shows the precedence and associativity of C++ operators (from highest to lowest precedence). Operators with the same precedence number have equal precedence unless another relationship is explicitly forced by parentheses.

| Operator Description | Operator | Alternative |
|--|--|--|
| **Group 1 precedence, no associativity** |
| [Scope resolution](../cpp/scope-resolution-operator.md) | [`::`](../cpp/scope-resolution-operator.md) |
| **Group 2 precedence, left to right associativity** |
| [Member selection (object or pointer)](../cpp/member-access-operators-dot-and.md) | [`.` or `->`](../cpp/member-access-operators-dot-and.md) |
| [Array subscript](../cpp/subscript-operator.md) | [`[]`](../cpp/subscript-operator.md) |
| [Function call](../cpp/function-call-operator-parens.md) | [`()`](../cpp/function-call-operator-parens.md) |
| [Postfix increment](../cpp/postfix-increment-and-decrement-operators-increment-and-decrement.md) | [`++`](../cpp/postfix-increment-and-decrement-operators-increment-and-decrement.md) |
| [Postfix decrement](../cpp/postfix-increment-and-decrement-operators-increment-and-decrement.md) | [`--`](../cpp/postfix-increment-and-decrement-operators-increment-and-decrement.md) |
| [Type name](../cpp/typeid-operator.md) | [`typeid`](../cpp/typeid-operator.md) |
| [Constant type conversion](../cpp/const-cast-operator.md) | [`const_cast`](../cpp/const-cast-operator.md) |
| [Dynamic type conversion](../cpp/dynamic-cast-operator.md) | [`dynamic_cast`](../cpp/dynamic-cast-operator.md) |
| [Reinterpreted type conversion](../cpp/reinterpret-cast-operator.md) | [`reinterpret_cast`](../cpp/reinterpret-cast-operator.md) |
| [Static type conversion](../cpp/static-cast-operator.md) | [`static_cast`](../cpp/static-cast-operator.md) |
| **Group 3 precedence, right to left associativity** |
| [Size of object or type](../cpp/sizeof-operator.md) | [`sizeof`](../cpp/sizeof-operator.md) |
| [Prefix increment](../cpp/prefix-increment-and-decrement-operators-increment-and-decrement.md) | [`++`](../cpp/prefix-increment-and-decrement-operators-increment-and-decrement.md) |
| [Prefix decrement](../cpp/prefix-increment-and-decrement-operators-increment-and-decrement.md) | [`--`](../cpp/prefix-increment-and-decrement-operators-increment-and-decrement.md) |
| [One's complement](../cpp/one-s-complement-operator-tilde.md) | [`~`](../cpp/one-s-complement-operator-tilde.md) | **`compl`** |
| [Logical not](../cpp/logical-negation-operator-exclpt.md) | [`!`](../cpp/logical-negation-operator-exclpt.md) | **`not`** |
| [Unary negation](../cpp/unary-plus-and-negation-operators-plus-and.md) | [`-`](../cpp/unary-plus-and-negation-operators-plus-and.md) |
| [Unary plus](../cpp/unary-plus-and-negation-operators-plus-and.md) | [`+`](../cpp/unary-plus-and-negation-operators-plus-and.md) |
| [Address-of](../cpp/address-of-operator-amp.md) | [`&`](../cpp/address-of-operator-amp.md) |
| [Indirection](../cpp/indirection-operator-star.md) | [`*`](../cpp/indirection-operator-star.md) |
| [Create object](../cpp/new-operator-cpp.md) | [`new`](../cpp/new-operator-cpp.md) |
| [Destroy object](../cpp/delete-operator-cpp.md) | [`delete`](../cpp/delete-operator-cpp.md) |
| [Cast](../cpp/cast-operator-parens.md) | [`()`](../cpp/cast-operator-parens.md) |
| **Group 4 precedence, left to right associativity** |
| [Pointer-to-member (objects or pointers)](../cpp/pointer-to-member-operators-dot-star-and-star.md) | [`.*` or `->*`](../cpp/pointer-to-member-operators-dot-star-and-star.md) |
| **Group 5 precedence, left to right associativity** |
| [Multiplication](../cpp/multiplicative-operators-and-the-modulus-operator.md) | [`*`](../cpp/multiplicative-operators-and-the-modulus-operator.md) |
| [Division](../cpp/multiplicative-operators-and-the-modulus-operator.md) | [`/`](../cpp/multiplicative-operators-and-the-modulus-operator.md) |
| [Modulus](../cpp/multiplicative-operators-and-the-modulus-operator.md) | [`%`](../cpp/multiplicative-operators-and-the-modulus-operator.md) |
| **Group 6 precedence, left to right associativity** |
| [Addition](../cpp/additive-operators-plus-and.md) | [`+`](../cpp/additive-operators-plus-and.md) |
| [Subtraction](../cpp/additive-operators-plus-and.md) | [`-`](../cpp/additive-operators-plus-and.md) |
| **Group 7 precedence, left to right associativity** |
| [Left shift](../cpp/left-shift-and-right-shift-operators-input-and-output.md) | [`<<`](../cpp/left-shift-and-right-shift-operators-input-and-output.md) |
| [Right shift](../cpp/left-shift-and-right-shift-operators-input-and-output.md) | [`>>`](../cpp/left-shift-and-right-shift-operators-input-and-output.md) |
| **Group 8 precedence, left to right associativity** |
| [Less than](../cpp/relational-operators-equal-and-equal.md) | [`<`](../cpp/relational-operators-equal-and-equal.md) |
| [Greater than](../cpp/relational-operators-equal-and-equal.md) | [`>`](../cpp/relational-operators-equal-and-equal.md) |
| [Less than or equal to](../cpp/relational-operators-equal-and-equal.md) | [`<=`](../cpp/relational-operators-equal-and-equal.md) |
| [Greater than or equal to](../cpp/relational-operators-equal-and-equal.md) | [`>=`](../cpp/relational-operators-equal-and-equal.md) |
| **Group 9 precedence, left to right associativity** |
| [Equality](../cpp/equality-operators-equal-equal-and-exclpt-equal.md) | [`==`](../cpp/equality-operators-equal-equal-and-exclpt-equal.md) |
| [Inequality](../cpp/equality-operators-equal-equal-and-exclpt-equal.md) | [`!=`](../cpp/equality-operators-equal-equal-and-exclpt-equal.md) | **`not_eq`** |
| **Group 10 precedence left to right associativity** |
| [Bitwise AND](../cpp/bitwise-and-operator-amp.md) | [`&`](../cpp/bitwise-and-operator-amp.md) | **`bitand`** |
| **Group 11 precedence, left to right associativity** |
| [Bitwise exclusive OR](../cpp/bitwise-exclusive-or-operator-hat.md) | [`^`](../cpp/bitwise-exclusive-or-operator-hat.md) | **`xor`** |
| **Group 12 precedence, left to right associativity** |
| [Bitwise inclusive OR](../cpp/bitwise-inclusive-or-operator-pipe.md) | [`|`](../cpp/bitwise-inclusive-or-operator-pipe.md) | **`bitor`** |
| **Group 13 precedence, left to right associativity** |
| [Logical AND](../cpp/logical-and-operator-amp-amp.md) | [`&&`](../cpp/logical-and-operator-amp-amp.md) | **`and`** |
| **Group 14 precedence, left to right associativity** |
| [Logical OR](../cpp/logical-or-operator-pipe-pipe.md) | [`||`](../cpp/logical-or-operator-pipe-pipe.md) | **`or`** |
| **Group 15 precedence, right to left associativity** |
| [Conditional](../cpp/conditional-operator-q.md) | [`? :`](../cpp/conditional-operator-q.md) |
| [Assignment](../cpp/assignment-operators.md) | [`=`](../cpp/assignment-operators.md) |
| [Multiplication assignment](../cpp/assignment-operators.md) | [`*=`](../cpp/assignment-operators.md) |
| [Division assignment](../cpp/assignment-operators.md) | [`/=`](../cpp/assignment-operators.md) |
| [Modulus assignment](../cpp/assignment-operators.md) | [`%=`](../cpp/assignment-operators.md) |
| [Addition assignment](../cpp/assignment-operators.md) | [`+=`](../cpp/assignment-operators.md) |
| [Subtraction assignment](../cpp/assignment-operators.md) | [`-=`](../cpp/assignment-operators.md) |
| [Left-shift assignment](../cpp/assignment-operators.md) | [`<<=`](../cpp/assignment-operators.md) |
| [Right-shift assignment](../cpp/assignment-operators.md) | [`>>=`](../cpp/assignment-operators.md) |
| [Bitwise AND assignment](../cpp/assignment-operators.md) | [`&=`](../cpp/assignment-operators.md) | **`and_eq`** |
| [Bitwise inclusive OR assignment](../cpp/assignment-operators.md) | [`|=`](../cpp/assignment-operators.md) | **`or_eq`** |
| [Bitwise exclusive OR assignment](../cpp/assignment-operators.md) | [`^=`](../cpp/assignment-operators.md) | **`xor_eq`** |
| [throw expression](../cpp/try-throw-and-catch-statements-cpp.md) | [`throw`](../cpp/try-throw-and-catch-statements-cpp.md) |
| **Group 16 precedence, left to right associativity** |
| [Comma](../cpp/comma-operator.md) | [,](../cpp/comma-operator.md) |

