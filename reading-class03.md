## Primitives vs. Objects
- understanding of pros and cons of using primitives and wrapper classes in java is very important, because its impacts codes performance , memory usage and code readabilty .
+ 1. int datatype is primitive variable has a short space in memory , and has a faster acces time since it stores in directly in the memory . in other hand  Integer is wrapper class for int , object provide more functionality but slower acces time since its living in heap meamory
2. the default value of int is '0' while, the default value of Integer is null.
3. autoboxing is a process to convert primitive into object while unboxing to convert object wrapper-class into primitive.

---
## Exceptions in java (cathing and handling exceptions)
Catching and handling exceptions is a critical aspect of writing robust and reliable software applications. 

what are the categories of exceptions?
- Checked Exceptions : These exceptions typically represent conditions that a program can reasonably anticipate and recover from
+ Unchecked Exceptions (Runtime Exceptions): They usually represent programming errors or issues that are not under normal program control, like accessing an array index out of bounds, dividing by zero, or calling a method on a null reference.
* Errors: Unlike exceptions, which are generally recoverable, errors usually indicate critical problems that might be impossible to handle effectively ( OutOfMemoryError, StackOverflowError, ThreadDeath.)

---

## Using Scanner to read in a file in Java
Using the Scanner class to read in a file in Java is a versatile and convenient way to process the contents of a file.

what are the advantages of it?
1. Simplicity and Ease of Use:
Using the Scanner class is relatively simple and intuitive. Its methods, such as next(), nextInt(), nextLine(), etc.
2. Flexible Data Extraction:
Scanner provides methods to extract different types of data, which can be particularly useful when reading structured data files that contain a mix of numbers, strings, and other data types.
3. Whitespace Handling:
Scanner automatically handles whitespace characters like spaces, tabs, and line breaks. This simplifies the process of reading data from files with irregular formatting.



