# vanilla-js-input-mask
add the **masked** class to the field to hang the handler

add the **prefixed** class to the field to use prefixes

set data-attribute for the input:
```
  data-pattern="+*(***)***-**-**"
```
asterisks will be replaced with the entered characters
```
data-prefix="+9"
```
the prefix will be added to the beginning of the field
example:
```
<input class='masked prefixed' type="tel" data-pattern="+**(***) *(**)-**-**" data-prefix="+99(888)"
 placeholder="+99(888) 1(23)-45-67">
```

##N.B.
the number of characters in the pattern is the number of characters that can be entered
