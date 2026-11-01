# Some stuff about Java.

## Useful things:
```
fori
iter
sout
psvm
```

## Some info about _ArrayList<>_

### For example we have an object of _ArrayList<>_ -> **obj**

```
obj.get(int index);
obj.add(Obj object);
obj.remove(Obj object);
obj.clear();
```
#### ArrayList can be in the List! (ArrayList<ArrayList<String>>)

----

## Some info about _HashMap<>_

### For example we have an object of _HashMap<>_ -> **obj**

```
obj.set(key);
obj.put(key, value);
obj.remove(key);
obj.clear()
obj.containsKey(key);
obj.containsValue(value);
obj.values();
obj.setKey();
```
---

## Some info about _Wrapper classes_

#### Wrapper classes:
```
Byte
Short
Integer
Long

Float
Double

Char
String

Boolean
```

#### We can change our types:
```
String numberStr = "123";

int numberInt = Integer.parseInt(number);
```

##### Or like this
```
short numberShort = 15_000;

int numberInt = (int) numberShort;
```
but we should be careful!  If we wanna change int to short or another types  be careful about numbers!

#### We also can use these methods:
```
int number1 = 1;
int number2 = 2;

int maxNumber = Integer.max(number1, number2);
int minNumber = Integer.min(number1, number2);
```

---

## Some info about _String.format_

```
String name = "Alex";
int age = 17;

String message = String.format(
    "Hello! Your name is %s, and you have %d years old!", name, age);

System.out.printf(
    "Hello! Your name is %s, and you have %d years old!", name, age");
```

#### Markers:
```
%s - String
%d - byte, short, int, long 
(%03d - if we have int = 5 -> 005)
(%,d - if we have int = 1000000 -> 1 000 000)
%f - float, double
(%.2f - if we have float/double = 0.123456 -> 0.12)
%b - boolean
%n - it's like \n
```