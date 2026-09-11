### General rules
- a primary key can be used to fetch data from any column in the table
	- it must be unique

### 1st normal form rules
- each column should contain atomic values
- a column should contain values that are of the same type
- each column should have a unique name
- order in which data is saved doesnt matter

example of atomic values:
![[Pasted image 20260302091004.png]]
![[Pasted image 20260302090851.png]]
here one student can take multiple subjects, however each value must be atomic so we separate the data into different rows

### 2nd normal form rules
Dependency is when one value can be used to fetch data from other values in a row. The primary key can be used to fetch any value in a table.
For a table to be in the 2nd normal form:
- It has to be in the 1st normal form 
- It must not have any partial dependencies

In summary, a table in the 2nd normal form must be fully dependent on the primary key, and any partial dependencies must be removed. There are many different ways to do this, but the ultimate objective is to remove the partial dependency from the table.

### 3rd normal form rules:
For a table to be in the 3rd normal form:
- it must not have transitive dependencies