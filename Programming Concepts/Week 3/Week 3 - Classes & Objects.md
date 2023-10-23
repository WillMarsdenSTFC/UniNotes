# **Constructors**

```java
public class week3 {

	public class Student {

		// Initialise variables.
		// Private means it can't be accessed without get methods.
		private int ID;
		private String Name;


		// Constructor Method.
		// Accessible via the "New" keyword.
		public Student(int idNumber, String studentName) {
			ID = idNumber;
			Name = studentName;
		}


		// Returns the private variable.
		public int getID() {
			return ID;
		}


		// Returns the private variable.
		public String getName() {
			return Name;
		}

		// Changes the private variable.
		public void setID(int newID) {
			ID = newID;
		}

		// Changes the private variable.
		public void setName(int newName) {
			Name = newName;
		}


	}

}
```