2.Boundary Value Analysis (BVA)
**answer:**
->**We can test:**
7 (just below min)
8 (min)
9 (just above min)
19 (just below max)
20 (max)
21 (just above max)

->**Boundary Value Test Cases**

**Test Case ID	     Input Length	     Example	         Expected Result**
   TC01	                 7	        "abc1234"	          Error message
   TC02	                 8	        "abc12345"	          Accepted
   TC03	                 9	        "abc123456"	          Accepted
   TC04	                 19	      19-char password	      Accepted
   TC05	                 20       20-char password	      Accepted
   TC06	                 21	      21-char password	    Error message

Equivalence Partitioning divides the input into valid and invalid groups and tests one value from each group.
Boundary Value Analysis focuses on testing the minimum and maximum limits and values around them.
