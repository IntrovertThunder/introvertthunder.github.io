---
layout: post
title:  "[Pythone-1-3] Python Basic Grammars"
date:   2017-07-15
excerpt: "Introduce Python Basic Grammars"
tag:
- python
- grammars
---


## Basic Grammar

### Pythone Commenting
* single line commenting : #
* multiple lines commenting : """ ~ """ (3 double quotation marks)


### Calculation
```javascript
  >>> 1+2
  3

  >>> 5/10
  0.5

  >>> 4*0.2
  0.8

  >>> a=1
  >>> b=2
  >>> a+b
  3

  >>> a="This is a String value"
  >>> print(a)
  This is a String value
```

### Calculation of Complex Number "j"
```javascript
  >>> a=3+4j
  >>> b=2
  >>> a*b
  6+8j
```


### Conditional Operation "if"
```javascript
  >>> a=10;
  >>> if a>0:
  ... [tab/space]print("a is greater than 0");
  ... [enter]
  a is greater than 0
```


### Loop Operation "for"
```javascript
  >>> for x in range(0, 3):
  ... [tab/space]print("number = %d" % x);
  ... [enter]
  number = 0
  number = 1
  number = 2
```

### Loop Operation "while"
```javascript
  >>> x = 1;
  >>> while (x<3):
  ... [tab/space]pring("print this while x=%d is smaller than 3" % x)
  ... x += 1
  ... [enter]
  print this while x=1 is smaller than 3
  print this while x=2 is smaller than 3
```

### Function "def"
```javascript
>>> def sum(x, y):
... [tab/space]return x+y
... [enter]
>>> print(sum(1, 2))
3
```
