# Java Fundamentals Cheat Sheet

### Declaring Variables

```
byte age = 30;
long viewsCount = 3_123_456L;
float price = 10.99F;
char letter = ‘A’;
boolean isEligible = true;
```

### Arithmetic

```
int x = 10 + 3;
int x = 10 - 3;
int x = 10 * 3;
int x = 10 / 3;
float x = (float)10 / (float)3;
```

### Interative Statements

```
for (condition) {expression}
for (int i: someArray) {}  
while (condition) {expression}
do {expression} while(condition)

```

### Decisive Statements

```
if (condition) {expression} 
if (condition) {expression} else {expression} 
switch (var) 
{ case 1: expression; break; default: expression; break; }
```

### Single Dimensional Array
```
type[] varName= new type[size];
type[] varName= new type[]{values1, value2,...};
```

### Multi Dimensional Array

```
datatype[][] varName  =  new dataType[row][col];
datatype[][] varName  =  {{value1, value2....},{value1, value2....}..};

```