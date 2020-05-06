# Compare Dart Vs Kotlin
 For self-study purposes, the similarities and differences of Dart vs Kotlin are reviewed.

### Comments
a special text that will be ignored by the compiler
* End-of-line comments

    *Kotlin | Dart*
```
// The line below will be ignored
```
* Multi-line comments
    *Kotlin | Dart *
```
/*  This is an example of
        a multi-line comment */
```

### Variables Declaration
* Variable Declaration

*Kotlin* 
```
val/var identifier: Type = initialization
```
*Dart* 
```
Type identifier = initialization;
```
Examples Kotlin
```
val text: String = 'Hello, I am studying Kotlin now.'
val n: Int = 1
```
Examples Dart
```
  String value = 'Hello world';
  int n = 1;
```

* Type inference.

*Kotlin* 
```
  val prefix = "Mr"
  val greeting = "Smith"
```

*Dart* 
```
  var prefix = 'Mr';
  var greeting = 'Smith';
```


* Immutable variables

*Kotlin* 
```
  val prefix = "Mr"
  val greeting = "Smith"
 
```

*Dart* 
```
   final prefix = 'Mr';
   final greeting = 'Smith';

```
Use const for variables that you want to be compile-time constants

*Kotlin* 
```
    const val SUBSYSTEM_DEPRECATED: String = "This subsystem is deprecated"
```

*Dart* 
```
   const bar = 1000000; // Unit of pressure (dynes/cm2)
   const double atm = 1.01325 * bar; // Standard atmosphere

```

##Built-in types

###Basic information about Int and Long types

*Kotlin* 
```
 val two = 2  // Int
 val ten = 10 // Int
  
 val twelve = two + ten // 12
 val eight = ten - two  // 8
 val twenty = two * ten // 20
 val five = ten / two   // 5
 val zero = ten % two   // 0, no remainder

```

*Dart* 
```
  var two = 2; // Int
  var ten = 10; // Int

  var twelve = two + ten; // 12
  var eight = ten - two; // 8
  var twenty = two * ten; // 20
  var five = ten / two; // 5
  var zero = ten % two; // 0, no remainder
```

*Kotlin* 
```
val longNumber1 = 1_000_000_000_000_000
val longNumber2: Long = 1_000_000
val longNumber3 = 1000L
 
val result = longNumber1 + longNumber2 - longNumber3
```
*Dart* 
```
  var longNumber1 = 1000000000000000;
  var longNumber2 = 1000000;
  double longNumber3 = 1000;

  var result = longNumber1 + longNumber2 - longNumber3;
```