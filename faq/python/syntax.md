<br>
<br>
## Syntax
<br>
#### FAQ >> Python >> Syntax
--------------------------------

Many people will often have their program broken because of one simple
error. If your error message says this, you will find this article
helpful.

`SyntaxError`

In Python, every code block starts with a colon, then is indented four
spaces, or one tab. Also, in if statements, where you test for equality, you use `==` instead of `=`. Here is
an example.

<br>
```
if True == True:
    print("Hello World!")
```
<br>
Another common error tells you there is an error on a line that
doesn't exist, which usually means you are missing something.

<br>
```
try:
  print("Hello World")
```
<br>
In this example, you are missing a `except` statement. Try this:
<br>
```
try:
  print("Hello World")
except KeyboardInterrupt:
  exit()
```
  
Following these rules can save a lot of time debugging for nothing.
**NOTE:** Python uses `elif` instead of `else if`.

