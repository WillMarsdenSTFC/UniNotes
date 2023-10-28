
```java
import java.utils.ArrayList;
```

# **ArrayList**
```java
// Creates an ArrayList with the data type String.
ArrayList<String> testArray = new ArrayList<String>();
```


**Add items to ArrayList**
```java
// Adds to the ArrayList and increments the pointer of the index.
testArray.add("Test1");
testArray.add("Test2");
```


**Get items from ArrayList**
```java
testArray.get(index);
String testIndex = testArray.get(0);
System.out.println(testIndex);

// Output: Test1
```


**Modify item in ArrayList**
```java
testArray.add("Test4");
testArray.set(2, "Test3");
System.out.println(testArray);

// Output: Test1, Test2, Test3
```

**Remove item in ArrayList**
```java
testArray.add("Test4");
testArray.remove(4);
System.out.println(testArray);

// Output: Test1, Test2, Test3
```

**Remove all items in ArrayList
```java
testArray.clear();
```

**ArrayList size**
Count starts at 1, counting the elements in the array.
```java
int sizeOfArray = testArray.size();
System.out.println(sizeOfArray);

// Output: 3
```

**For each loop**
```java
for (String i : testArray) {
	System.out.println(i);
}

// Output: Test1, Test2, Test3
```