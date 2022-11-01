# Learning-Java

## These notes emphasize key differences between Java with JavaScript

### Java has an enhanced for loop for iterables:
```
Collection<Date> dates=...
for(Date date : dates)
  System.out.printLn(date);
```


### Js only has Number.parseInt() and parseFloat(), but Java has:
Byte.parseByte(), Integer.parseInt(), Long.parseLong(),Float.parse(float),Double.parseDouble,Boolean.parseBoolean()
new Scanner(str).nextByte(), nextInt()....

### Java creates array with given lenth:
```
String[] strs = new String[5]
```
Unassgined slots will be null or 0

### Java use curly braces for array content:
```
int[] primes={2,5,7}
new Animal [] {dog, cat}
```
