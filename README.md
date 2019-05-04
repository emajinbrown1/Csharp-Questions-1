# Csharp-Questions-1
## **What is a namepspace?** ##
### *A namespace is used to organize different levels of code* ###
>The biggest advantage of using namespace is that the class names which are declared in one namespace will not clash with the same class names declared in another namespace

[Namespaces](https://www.markdownguide.org/cheat-sheet/)

## **What are value types?** ##
### *A value type is a variable that has a certain type* ###
[ValueTypes](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/value-types)

## **What are reference types?** ##
### *A reference type is a value that implements interfaces* ###
[ReferemceTypes](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/reference-types)

## **What is a automatic property and how is it useful?** ##
### *A automatic property is a property of C# and this is useful because it makes the property more concise when there's no additional logic required* ###
>When you use Auto implemented properties , compiler creates the private fields in the background

## **What is the purpose of using statement?** ##
### *The purpose of the using statement is to dispose object specified in the using block once it's not needed anymore* ###
>The statement calls the Dispose method on the object in the correct way, and (when you use it as shown earlier) it also causes the object itself to go out of scope as soon as Dispose is called.

## **What are dynamic type variables** ##
### *A dynamic type variable is a language in which variables are used to compile time*

## **What is the purpose of the is operator?** ##
### *The purpose of the is operator is to check if an object with a given type and it returns the result as boolean* ###
[ISoperator](https://stackoverflow.com/questions/3786361/difference-between-is-and-as-keyword)

## **What are generics and how is using them useful?** ##
### *Generics are classes that allow user to explain a class with the placeholder* ###
[Generics](https://www.youtube.com/watch?v=gyal6TbgmSU)

## **What is the scope of a public member of a class?** ##
### *Public access allows a class to expose its member variables and member functions to others* ###
>When the scope of a declaration extends to or past the end of a class definition, the regions defined by the member definitions of that class are included in the scope of the class.
>Members defined lexically outside of the class are also in this scope

## **Can you create a function that can accept a varying number of arguments?** ##
### *Yes it is possible to create a function that can except a varying number of arguments to a method, it just comes with some restrictions* ###
1.The variable number of parameters must all be the same type
2.They are treated as an array within the method
3.They must be the last parameter of the method

## **How do you sort an array?** ##
### *You first sort an array using array.sort() method which puts the array in ascending order. Then you could reverse it using array.reverse() method.* ###
[SortingArrays](http://www.csharp-examples.net/sort-array/)

## **What is a nullable type and what purpose does it serve?** ##
### *A nullable type can represent the range of values for its underlying value type* ###
- Nullable types represent value-type variables that can be assigned the null value. You cannot create a nullable type based on a reference type. (Reference types already support the null value.)

## **What is an enumeration?** ##
### *Enumeration is a set of named interger constants* ###

## **What is inheritance** ##
### *Inheritance is the ability to create a class that has the attributes from an existing class* ###
[Inheritance](https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/inheritance)

## **Is multiple inheritance supported?** ##
### *No multiple inheritance is not excepted* ###

## **What is the purpose of as operator?** ##
### *The operator is used to check if the run time type of an object goes with the given type* ###
[AsOperator](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/as)

## **What is an object?** ##
### *An object is an instance of a class that is created dynamically*
- In general, object type is useful where there is a requirement to build generic routines.
- values of any type can be assigned to variables of object type, object type is used mostly in designing classes that handle objects of any type that allow code to be reused. 

## **What is the difference between a struct and a class?**
### *The difference between struct and class is that structs are value types and classes are reference types*

## **What is the difference between continue and break statements?** ##
### *The difference between continue and break is that continue is used when you want to skip one or more statements in the loop and break is when the loop is exited immediately*

## **What is this and how is it used?**
### *This is used to refer to the current instance of the class*
[ThisStatement](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/this)

## **What is try and catch and when are they used?**
### *A try block identifies a block of code for which exceptions are activated and a catch block catches the exception at the place in the program where you want to handle the problem.*

## **How is exception handling done?**
### *Exception handling is done through the try, catch, finally, and throw methods*

## **What is finally and what is its purpose?**
### *Finally is usesd to execute a given set of statements whether an exception is thrown or not and its purpose is to make sure mulitple files aren't open at once.*

## **List the differences between Array and ArrayList.**
### *Array*
- Simple fixed sized arrays
- Basic functionality provided by Java
- Array members are accessed using [] 
### *ArrayList*
- Dynamic sized arrays in Java that implement List interface
- Part of collection framework in Java
- A set of methods to access elements and modify them

## **Define constructor.**
### *Constructors initailize the data of new memembers of the new object*
>Constructors have the same name as the class or struct, and they usually initialize the data members of the new object.

## **When can var be used to declare a variable and how is the type for the variable determined?**
### *Var can be used when you are declaring an implicit variable and the variable is determined when you are assigning values variables.*

## **What is an abstract class?**
### *An abstract class is designed to be inherited by subclasses that either implement or override its methods.*

## **What is an interface?**
### *An interface contains only the declaration of the methods, properties, and events, but not the implementation.*

## **What is a method?**
### *A method is a code block that contains a series of statements*

## **What is a property?**
### *A property is a member that provides a mechanism to read, write, and compute values.*

## **What is an access specifier?**
### *A access specifier is keywords to specify the accessibility of a type of it members.*

## **What access specifiers are supported and what do they mean?**
**public**
- The type or member can be accessed by any other code in the same assembly or another assembly that references it.

**private**
- The type or member can be accessed only by code in the same class or struct.

**protected**
- The type or member can be accessed only by code in the same class, or in a class that is derived from that class.

**internal**
- The type or member can be accessed by any code in the same assembly, but not from another assembly.

**protected internal** 
- The type or member can be accessed by any code in the assembly in which it is declared, or from within a derived class in another assembly.

**private protected** 
- The type or member can be accessed only within its declaring assembly, by code in the same class or in a type that is derived from that class.

## **What is a collection?**
### *A collection gets memory dynamically to elements and accessing a list of items.*

## **What is a Hash Table?**
### *A hash table is a collection of key value pairs that are organized based on the hash code*

