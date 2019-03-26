#include<stdio.h>

int main(void)
{
    int number[4], i;
    int MaxNumber=0, Firstarray, MinNum=0 ;
	//
    for(i=0; i<4; i++)
    {
        scanf("%d",&number[i]);

        // Condition for Maximum number
        if(number[i] > MaxNumber)
        {
            MaxNumber = number[i];
        }

    }
    Firstarray = number[0];
    MinNum = number[0];

    for( i=0; i<4; i++)
	{
		// Condition for Minimum number


			if( number[i] < MinNum )
				MinNum = number[i];

	}

    printf("The maximum age is %d\n",MaxNumber);
    printf("The minimum age is %d\n",MinNum);
    return 0;
}

