# Exception Handling in Java

## Definitions
- An `exception` is an abnormal condition that occurs at run-time.  
Or we can say that,  
- An `exception` is a run-time error.
- Catching an `exception` in Java and processing it is called `Exception Handling`.
- In Java, we have objects for exceptions that describe the error that has occurred in the code at run-time.

## What happens when an exception (run-time error) occurs?
1. When an exception (run-time error) occurs, an object (which contains information about the exception)
is created and `thrown` in the method that has created the error.  
2. Either the method can "handle" the exception itself, or it can pass it to some other method.
3. At some point, the exception will be `caught` by a method, and will be processed.  
  
**NOTE:**  Exceptions can be automatically generated by the Java Run-Time Environment, or they can be generated manually by the code that we have written.

## Keywords for handling Exceptions in Java
1. `try`.
2. `catch`.
3. `throw`.
4. `throws`.
5. `finally`.

## Hierarchy of Exceptions in Java
![](img/exceptionHierarchy.png)  

  