```c
/***** FUCK IT IM BORED LETS REMAKE QUADRATIC EQUATION TO C LANGUAGE *****/

#include <stdio.h>
#include <math.h>


int main() 
{
    int a, b, c;
    double Numerator1, Numerator2, Denominator, Calculation1, Calculation2;
    
    printf("Enter your value for 'a': ");
    scanf("%d", & a);
    
    printf("\nEnter your value for 'b': ");
    scanf("%d", & b); 
    
    printf("\nEnter your value for 'c': ");
    scanf("%d", & c);
    
    Numerator1 = (-b + sqrt(powf(b, 2) - 4 * a * c));
    Numerator2 = (-b - sqrt(powf(b, 2) - 4 * a * c));
    Denominator = 2 * a;
    
    Calculation1 = Numerator1 / Denominator;
    Calculation2 = Numerator2 / Denominator;
    
    printf("\n/===== THE ROOTS =====/\n");
    printf("\nRoot 1\n X = %.3f", Calculation1);
    printf("\nRoot 2\n X = %.3f", Calculation2);
    
    return 0;
}
```
