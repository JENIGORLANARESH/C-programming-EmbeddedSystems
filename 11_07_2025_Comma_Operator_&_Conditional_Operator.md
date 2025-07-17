# Comma Operator 

* Multiple expressions can be mentioned in the same line.

int a = 8, b = 7, c = 9, d = a + b + c;

* General expressions are evaluated from left to right.

```
/*

int i , j = 0;
i = j, j + i;
printf("%d %d", i,   j);
                10   10

*/
```

* (  )  paranthesis changes the order of evaluation.

* Right most expression get assigned to i.
* The statements inside the paranthesis are evaluated first.

```
//    Left  ------>  Right

      i = ( j   ,  j + 1 );       
      11    10       11           
//    ^______________|
```

```
      i  =  (  j + 1 ,  j  );
//    ^_________________|

```

```

      int a , b, c, sum;
      sum  =  (  a = 8,  b = 7,  c = 9, a + b + c );
//     ^                                   24
//     |___________________________________|

```

```

      int i = 10 , j = 20;
      i  =  (  i = i + j  ,  j = i - j , i - j);

//    [  i  = 20 , j  =  10  ]

```


```
      int i , j = 10;
      i = ( j , j++ );
//    ^     10  10
//    |_________|
      
      printf("%d %d", i ,  j );
//                    10   11
```

```
      int i , j = 10;
      i = ( j , ++j );
//    ^     10   11
//    |___________|

      printf("%d %d", i , j );
//                   11   11
```

```
      int a = 8 , b = 7 , temp ;

      temp = a , a = b , b = temp;
//    ^      8   ^   7   ^    8
//    |______|   |___|   |____|
```
