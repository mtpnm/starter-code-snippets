### Basic hello world program
```java
class HelloWorld {
    public static void main() {
        System.out.println("hello world");
    } 
}
```

### Basic types
```java
class HelloWorld {
    public static void main() {
        // numbers are represented as int
        int myNumber = 10; // int, short for integer is a type in java
        
        // print the number
        System.out.println(myNumber);
        
        // strings to store 2 or more characters
        String myName = "john smith"; // just like int, string is a type
        
        // print the string
        System.out.println(myName);
    }
}
```

### Basic integer operations (add, subtract, divide, multiply)
```java
class HelloWorld {
    public static void main(String[] args) {
        int x = 10;
        int y = 20;
        
        int additionResult = x + y; // add two numbers. a variable to store the result
        System.out.println(additionResult);
        System.out.println(y-x); // subtract
        System.out.println(y/x); // divide
        System.out.println(y*x); // multiply 
    }
}
```

### Character vs a string
```java
class HelloWorld {
    public static void main(String[] args) {
        // to represent a single character such as `a` or `b` you need to wrap
        // it in single quotes.
        char myCharacter = 'a';
        
        // to represent strings, a minimum of 2 or more characters are need.
        // use double quotes to wrap in strings.
        string myName = "john smith";
    }
}
```


### String operations
```java
class HelloWorld {
    public static void main(String[] args) {
        String firstName = "john";
        String lastName = "smith";
        String fullName = firstName + ' ' + lastName;
        
        System.out.println(fullName);
    }
}
```
