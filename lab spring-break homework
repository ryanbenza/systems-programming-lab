\\number 1

int main()
 {
     int num1, num2, minmultiple;

     printf("inset two numbers: ");
     scanf("%d %d", &num1, &num2);
     
     minmultiple= (num1<num2) ? num1:num2 ;

     while(1) 
     {
         if( minmultiple % num1 == 0 && minmultiple % num2 == 0 )
         {
             printf("LCM = %d\n", minmultiple);
             break;
         }
         minmultiple++;
     }

     return 0;
 
 \\ number 2
 
 #include <stdio.h>
int main()
{
  int n, s = 0, t;

  printf("Enter a number to see if it is a palindrome or not a palindrome \n");
  scanf("%d", &n);

  t = n;

  while (t != 0)
  {
    s = s * 10;
    s = s + t%10;
    t = t/10;
  }

  if (n == s)
    printf("%d is a palindrome .\n", n);
  else
    printf("%d is not a palindrome .\n", n);

  return 0;
}

\\ number 3 
#include <stdio.h> 
  
int main() 
{ 
    int A, B, C; 
  
    printf("Enter the numbers A, B and C: "); 
    scanf("%d %d %d", &A, &B, &C); 
  
    if (A >= B && A >= C) 
        printf("%d is the largest number.", A); 
  
    if (B >= A && B >= C) 
        printf("%d is the largest number.", B); 
  
    if (C >= A && C >= B) 
        printf("%d is the largest number.", C); 
  
    return 0; 
}  

// Question 5
#include<stdio.h>
 
int main() 
{
   int i,c=0,n;
   int a=0;
   int b=1;
   printf("\nEnter a number to generate fibonacci series upto nth term\n");
   scanf("%d",&n); 
   printf("Fibonacci series upto %d term:-\n",n);
   while(c<=n)
   {
       printf("%d ",c);
       a=b;
       b=c;
       c=a+b;
   }
}  



\\ Number 4

#include<stdio.h>  
 int main()    
{    
int num, rev=0, rem;    
printf("Enter Your  number = ");    
  scanf("%d", &num);    
  while(num!=0)    
  {    
     rem=num%10;    
     rev=rev*10+rem;    
     num=num/10;    
  }    
  printf("Number after reversed = %d",rev);    
return 0;  
} 
