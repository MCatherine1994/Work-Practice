### SQL work notes:  
 
1. Convert julian date to the calendar date: 

``` 
  TO_DATE(TO_NUMBER(1900000 + TABLE_COLOUMN, '9999999'), 'YYYYDDD'）  
```  

2. Select distinct COLOUMN_NAME from TABLE_NAME  
  
3. Floor(n) returns largest integer equal to or less than n 
   Round(n, integer) round to the "integer" position, this places to the right of decimal point 
      
4. Table.Coloumn in (:listname) pops up a selection table (as a parameter) to let the user enter a value  
 
5. SYSDATE is the system date   
