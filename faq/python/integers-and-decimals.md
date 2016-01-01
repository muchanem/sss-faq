<br>
<br>
## Strings, Integers, and Floats
<br>
#### Faq >> Python >> Strings, Integers, and Floats
----------
There are 3 forms of items in python, integers, floats
(decimals), and Strings. 
<br>
---
***Integers***: `number = int("3")` - The `int` function turns the string
into and integer, which is assigned to the variable `number`. Since
you cannot join different types of values, you can either use commas
or use the `str()`.
```
print("Your number is ",number)
# Other way
print("Your number is " + str(number))
```
---
***Floats***: `decimal = float(3)` - The `float` function turns the
integer `3` into the float `3.0`, or the string “2.5" into the float `2.5`. These are joined the same ways
as integers.
```
print("Your decimal is ",decimal)
# Other way
print("Your decimal is " + float(number))
```
---
***Strings***: `text = str(3)` - The `str` function will convert the
integer `3` to the string `"3"`. Strings are **ALWAYS** wrapped in
quotes ("" or '') and can hold text. If you use the double quotes, you
may use single quotes without escaping them and vice versa. If you need to use
a double quote or a single quote in single quotes, escape it like this `\"` or `\'`.

