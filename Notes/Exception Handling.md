# Exception-Handling 

* A Java exception is an object that describes an exceptional(i.e, error) condition that has occurred in a piece of code.
* When an exceptional condition arsies, an object representing that exception is created and thrown in the method that caused the error.
* Exceptions can be generated by java run-time system, or they can be manually generated by your code.
  * Exceptions thrown by Java relate to fundamental errors that violate the rules of the java language or the
    constraints of the java execution
  * Manually generated exceptions are typically used to report some error condition to the caller of the method.
  
## Keywords

* Java Exceptions are handled by 5 keywords:
   * try
   * catch
   * throw
   * throws
   * finally

* Program statements that want to be monitored for exceptions are contained within a **try** block. If an exception occurs in try block, it is thrown.
* If an exception occurs in the try block, it is thrown, we can catch this exception using **catch** and handle in some rationak manner.
* To manually throw exception, use the keyword **throw**.
* Any exception that is thrown out of a method must be specified as such by a **throws** clause.
* Any code that absolutely must be executed after a **try** block completes is put in a **finally** block.

## Syntax

```
try {
  // block of code to monitor for errors
}
catch (ExceptionType1 exOb) {
  // exception handler for ExceptionType1
}
catch (ExceptionType2 exOb) {
  // exception handler for ExceptionType2
}
  
// ...

finally {
  // block of code to be executed after try block ends
}
```

## try-catch

```
try {
  // block of code to monitor for errors
}
catch (ExceptionType exOb) {
  // exception handler for ExceptionType
}
```

## throw

It is possible for your program to throw an exception explicitly, using the throw
statement

```
throw ThrowableInstance;
```
