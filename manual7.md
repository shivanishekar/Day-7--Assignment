1./ https://www.qa-practice.com/elements/input/passwd
For the above requirement, design Boundary Value Analysis and Equivalence Partition cases4
**answer :**
This page is a Password field validation page.
Assumption :
 Password length must be between 8 and 20 characters
 Required field

->**Equivalence Partitioning (EP)**
Dividing input data into valid and invalid groups (partitions).
From each group, we test at least one value.

Identify Partitions :If password length = 8 to 20
Valid Partition :8 to 20 characters

Invalid Partitions : Less than 8 characters
                     More than 20 characters 
                     Empty input

**Equivalence Partition Test Cases**
Test Case ID	         Input	                 Partition            Type	                         Expected Result
TC01	                (Empty)	                  Invalid          	Error: This field is required
TC02	              "abc" (3 chars)	          Invalid (<8)	       Show length error
TC03	            "password1" (9 chars)	     Valid	Accepted
TC04	            20 character password	     Valid	Accepted
TC05	            25 character password	      Invalid (>20)	       Show length error

