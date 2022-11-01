###Java String uses a method to get length instead of seeing length as a property
```
s.length()
```

###Java uses three double quotes to enclose multiline strings instead of back ticks
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
