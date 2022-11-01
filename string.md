### Java String uses a method to get length instead of seeing length as a property
```
s.length()
```

### Java uses three double quotes to enclose multiline strings instead of back ticks
```
""" some
string
"""
```
### Java can't use == to compare strings. Use equals(). // use equalsIgnoreCase() to ignore case
```
String a = "str"
String b ="String.valueOf(new Char []{'s','t','r'})"
a==b //false
a.equals(b) //true
```

### Java String uses contains() instead of includes()
### Java uses both strip() and trim()

###Java String additional methods:

compareTo()
endsWith(), startsWith()
intern()  //fetch string instance from global string pool
isBlank(), isEmpty()
lines()
regionMatches()
stripLeading(), stripTrailing() // remove whitespace

##String.valueOf(arg) return a string representing arg

