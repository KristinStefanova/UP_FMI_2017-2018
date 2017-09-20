# Quiz #6

**1. Погледнете следното:**
```c++
double values[3][5] = { {1.2, 9.0, 3.2},
			{9.2, 0.5, 1.5, -1.2},
    			{7.3, 7.9, 4.8} 
		      };
 ```
**каква е стойността на values[2][1]?**

А. 7.3

B. 7.9

C. 9.2

D. 0

  
**2. Погледнете следното:**
```c++
double values[3][5] = { {1.2, 9.0, 3.2},
			{9.2, 0.5, 1.5, -1.2},
    			{7.3, 7.9, 4.8} 
		      };
 ```
**каква е стойността на values[3][0]?**

А. 7.3

B. 7.9

C. 9.2

D. Няма такъв елемент
  
**3. Искате да създадете матрица, която изглежда така:**
	
	12	-9	8
	
	7	14
	
	-32	-1	0
**Кое от следните ще работи винаги?**


А.   
```c++
double table[3][3] = { 12, -9, 8, 
   			7, 14,
                      -32, -1, 0
		     };
```

B.   
```c++
double table[][3] =  { {12, -9, 8}, 
		       {7, 14, 0},
		       -32, -1, 0} 
		     };
```

C. 
```c++
double table[][] =  { {12, -9, 8}
    		      {7, 14}
        	      {-32, -1, 0} 
		     };
```

D.  
```c++
double table[3][3] = { {12, -9, 8},
    	               {7, 14},
   		       {-32, -1, 0} 
		     };

```  

**4. Имате следното:**
```c++
double things[][4] = { {1.2, 9.0},
    		       {9.2, 0.5, 0.0},
    		       {7.3, 7.9, 1.2, 3.9} 
		     };
```
**Каква е стойността на things[1][1]?**

А. 1.2

B. 0.5

C. 9.2

D. 0

**5. Имате следното:**
```c++
double things[][4] = { {1.2, 9.0},
    		       {9.2, 0.5, 0.0},
    		       {7.3, 7.9, 1.2, 3.9} 
		     };
```
**Каква е стойността на things[0][3]?**

А. 1.2

B. 7.3

C. 9.0

D. 0

  
**6. Какво е двумерен масив?(С едно изречение)**

  
**7. Имате следното:**
```c++
int items[][5] = { {0, 1, 3, 4},
    		   {4, 3, 99, 0, 7 },
   		   {3, 2} 
		 };
```
**Кой от следните оператори ще замести 99 с 66?**

А. items[1][2] = 66;

B. items[2][1] = 66;

C. items[99] = 66;

D. items[2][3] = 66;

  
**8. Кое от следните декларира двумерен масив с 5 цели(int) елемента на ред?**

A.    int[][5] array;

B.    int array[5];

C.    int array[5][];

D.    int array[][5];

  
**9. Имате следното:**
```c++
int items[3][5] = { {0, 1, 3, 4},
    		    {4, 3, 99, 0, 7 },
   		    {3, 2} 
		  };
```
**Koй от следните фрагменти ще принтира елементите на items?**

A.
```c++
for (int row = 0; row < 5; row++)
{
	cout << endl;
  	for (int col = 0; col < 3; col++)
  		cout << items[row][col] << " ";
}
```

B. 
```c++
for (int row = 0; row < 3; row++)
{
  	for (int col = 0; col < 5; col++)
  		cout << items[row][col] << " ";
}
```

C.  
```c++
for (int row = 0; row < 5; row++)
{
	for (int col = 0; col < 5; col++)
  		cout << items[row][col] << " ";
}
```

D.
```c++
for (int row = 0; row < 3; row++)
{
	cout << endl;
	for (int col = 0; col < 3; col++)
  		cout << items[row][col] << " ";
}
```

  
**10. Имате следното:**
```c++
int items[3][5] = { {0, 1, 3, 4},
    		    {4, 3, 99, 0, 7 },
   		    {3, 2} 
		  };
```
**Koй от следните фрагменти ще замени реда {0, 1, 3, 4} на items с реда {1, 2, 3}?**

A.   
```c++
items[0][0] = 1; 
items[0][1] = 2; 
items[0][2] = 3;
```

B.   
```c++
items[0] = {1, 2, 3};
```

C.     
```c++
int temp[] = {1, 2, 3};
items[0] = temp;
```

D. 
```c++
items[0][0] = 1; 
items[0][1] = 2; 
items[0][2] = 3;
items[0][3] = 0;
items[0][4] = 0;
```