
# **The Main Method** 

```java
public class Program {
	public static void main(String[] args) {
		// Code goes here
		// String name = "Will"
	}
}
```

# Inputs via Scanner

Firstly import the scanner class.

```java
import java.util.Scanner;
```

Create an object of the Scanner class.

```java
private Scanner reader = new Scanner(System.in);
```

The scanner then needs to read the next line.

```java
String name = reader.nextLine();
```

The scanner must be closed after use to prevent a memory leak.

```java
reader.Close();
```

# Static Methods

Dynamic members of a class would be accessed through an instance of an object. However, the main method is defined to be **static**, meaning that the method can be called through the class name. This allows it to be called without the need for an object and no "new" keyword is needed.

Example:

```java
Class newClass = new Class();
```

Can become:

```java
string Class = Class():
```


# Constants

Constants can be assigned using the "final" keyword, variable names typically are uppercase and using underscores to symbolise spaces.

```java
final int HOURS_IN_DAY = 24;
```



