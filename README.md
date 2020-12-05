#include <stdio.h>

 

void main()

{

    int i;

    // first day got 10 cent

    double sum = 0.10;

    // start on 2nd day, got twice

    for(i = 2; i <= 15;)

    {

        // the next day got twice the previous day

        sum = sum + sum;

        printf("Total money for day %d is USD%.2f\n", i, sum);

        // after complete the calculation, go to the next day

        i++;

    }

}
