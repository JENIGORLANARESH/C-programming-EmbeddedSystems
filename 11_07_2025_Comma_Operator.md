# Comma Operator 

* Multiple expressions can be mentioned in the same line.
      int a = 8, b = 7, c = 9, d = a + b + c;

* General expressions are evaluated from left to right.

  int i , j = 0;
  i = j, j + i;
  printf("%d %d", i,   j);
                  10   10

* (  )  paranthesis changes the order of evaluation.

        L  ------>  R
  i = ( j   ,  j + 1 );       * Right most expression get assigned to i.
  11    10       11           * The statements inside the paranthesis are evaluated first.
  ^______________|

  i  =  (  j + 1 ,  j  );
  ^_________________|

  *    int a , b, c, sum;
        sum  =  (  a = 8,  b = 7,  c = 9, a + b + c );
         ^                                   24
         |___________________________________|

  *    int i = 10 , j = 20;
        i =  (
