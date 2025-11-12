This section contains everything about if statements. Also notice how, unlike Python, these statements don't require indentation (you should still indent though), they just require a 'then' and 'end' keyword. Furthermore, expressions need to be encased in parentheses.
### If statement
```text 
if (5 > 3) then
	display("5 is greater than 3")
end
```

### Else if statements
```text 
x = 10
if (x == 2) then
	display("x equals 2")
butif (x == 10) then
	display("x equals 10")
end
```

### Else statements
```text 
x = 15
if (x == 2) then
	display("x equals 2")
butif (x == 10) then
	display("x equals 10")
otherwise
	display("x is not 2 or 10")
end
```

Lastly, as mentioned in [[index|Getting Started]], all Boolean algebra and logic operations work the same as Python and can be seen below:
```text
!= -> Not equal to
== -> Equal to
> -> Greater than
< -> Less than
>= -> Greater than or equal to
<= -> Less than or equal to
and
or
not
```