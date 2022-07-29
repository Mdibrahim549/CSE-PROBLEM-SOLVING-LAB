# CSE-PROBLEM-SOLVING-LAB
#include <stdio.h>
int main ()
{
    int num;
    printf("Enter your number: ");
    scanf("%d",&num);
    if(num>100)
    {
    	printf("%d is wrong number");
    }
    else if(num>=80)
    {
    	printf("Your grade is A+\n Your point is 4:00");
    }
    else if(num>=75)
    {
    	printf("Your grade is A\n Your point is 3:75");
    }
    else if(num>=70)
    {
    	printf("Your grade is A-\n Your point is 3:50");
    }
    else if(num>=65)
    {
        printf("Your grade is B+\n Your point is 3:25");
    }
    else if(num>=60)
    {
    	printf("Your grade is B\n Your point is 3:00");
    }
    else if(num>=55)
    {
    	printf("Your grade is B-\n Your point is 2:75");
    }
    else if(num>=50)
    {
    	printf("Your grade is C+\n Your point is 2:50");
    }
    else if(num>=45)
    {
    	printf("Your grade is C\n Your point is 2:25");
    }
    else if(num>=40)
    {
    	printf("Your grade is C-\n Your point is 2:00");
    }
    else if(num>=0)
    {
    	printf("Your grade is F\n Your point is 0:00");
    }
}
