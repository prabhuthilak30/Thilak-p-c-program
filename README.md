# Thilak-p-c-program
// // Online C compiler to run C program online
// #include <stdio.h>

// int main() {
//       int a;
//       printf("enter a number");
//       scanf("%d",&a);
//       if(a<20)
//       { printf("a is lesser than 20");
 
//       }
//       else(a>20);
//       {printf("a is greater than 20");}

//     return 0;
// }


// #include<stdio.h>
// int main()
// { int a;
// printf("enter a number");
// scanf("%d",&a);
// if(a<0)
// {printf(" a is negative");
// }
// else if(a>0)
// { printf(" a is positive number");
// }
// else
// { printf(" a is equal to zero");
// }
 
// }

//  #include<stdio.h>
//  int main()
//  { int i,n;
//  printf(" enter a number for table");
//  scanf("%d",&n);
//  for(i=1;i<=10;i++)
//  { printf("%dx%d=%d\n",n,i,i*n);}}

// #include<stdio.h>
// int main()
// { int a;
// printf("enter a number");
// scanf("%d",&a);
// for(a=1;a<=50;a++)
// { if (a%2==0)
// { printf("%d\n",a);}}}

// int sumOfDigits(int n)
// { int sum=0;
//  while(n>0)
//  {sum+rfcf=n%10;
//  n=n/10;
//  }
//  return sum;}



// int checkYear(int n) {
//     // code here
//      printf("enter A year");
//      scanf("%d",&n);
//      if(n%400==0 && n%4==0)
//      { printf("it is a leap year");}
//      else
//      { printf(" not a leap year");
//      }
// }

 
#include <stdio.h>

// int main() {
//       int n,reversed=0,remainder;
//      printf("enter a sequence of number");
//       scanf("%d",&n);
//       while(n!=0)
//      {
//          remainder=n%10;
//          reversed=reversed*10+remainder;
//          n=n/10;
//      }
//      if(n=reversed)
//      { printf("it is a palindrome");
//      }
//      else
//      { printf("not a palindrome");}

//     return 0;
//  }


#include <stdio.h>

int main() {
    int n, i, con=0;

    printf("Enter a number: ");
    scanf("%d", &n);

    if (n <= 1) {
        printf("Not a prime number");
    } else {
        for (i = 2; i <= n / 2; i++) {
            if (n % i == 0) {
                con = 1;
                break;
            }
        }

        if (con == 0)
            printf("Prime number");
        else
            printf("Not a prime number");
    }

    return 0;
}



#include <stdio.h>

// int main() {
//     int day;
//     printf("enter the number");
//     scanf("%d",&day);
//     switch(day)
//     {
//         case 1:
//         printf("monday");
//         break;
//         case 2:
//         printf("tuesday");
//         break;
//         case 3:
//         printf("wednesday");
//         break;
//         case 4:
//         printf("thursday");
//         break;
//         case 5:
//         printf("friday");
//         break;
//         case 6:
//         printf("saturday");
//         break;
//         case 7:
//         printf("sunday");
//         break;
 
//     }
 
 

//     return 0;
// }




#include<stdio.h>
// int main()
// {
//     int n,first=0,second=1,next,i;
//     printf("enter the number of terms");
//     scanf("%d",&n);
//     printf("fibonacci series");
//     for(i-1;i<=n;i++)
//     { printf("\n%d",first);
//     next=first+second;
//     first=second;
//     second=next;
//     }
// }





// #include<stdio.h>
// int main()
// { int a,b,temp;
// printf("enter a  two number");
// scanf("%d%d",&a,&b);
// temp=a;
// a=b;
// b=temp;
// printf("a=%d\n",a);
// printf("b=%d\n",b);
 
// }


// #include<stdio.h>
// int main()
// {  int a;
// printf("enter a number");
// scanf("%d",&a);
// if(a%2==0)
// { printf("it isa even");
// }
// else
// { printf(" it is a odd");}}


// #include<stdio.h>
// int main()
// { int a,b,c;
// printf(" enter a three numbder");
// scanf("%d%d%d",&a,&b,&c);
// if(a>b&&a>c)
// { printf("a is largest");
// }
// else if(b>a&&b>c)
// { printf(" b is a large");
// }
// else
// { printf("c is a large");
// }}


#include<stdio.h>
// int main()
// { int a,b,c;
// printf("enter three number");
// scanf("%d%d%d",&a,&b,&c);
// if(a<b&&a>c||a>b&&a<c)
// { printf(" a is the second highest");
// }
// else if(b<a&&b>c||b>a&&b<c)
// {printf(" b is the second highest");
// }
// else
// { printf("c is the second highest");
// }}


// #include<stdio.h>

// int sum(int a,int b)
// { int sum;
//     sum=a+b;
// printf("sum=%d",sum);
// }
// int main()
// { int a,b;
//     printf("enter two numbwer");
//     scanf("%d%d",&a,&b);
//     sum(a,b);
// }
 

#include <stdio.h>

// int main() {
//      int n,reversed=0,remainder;
//      printf("enter a sequence of number");
//      scanf("%d",&n);
//      while(n!=0)
//      {
//          remainder=n%10;
//          reversed=reversed*10+remainder;
//          n=n/10;
//      }
//      printf("the reversed is%d",reversed);

//     return 0;
// }



#include <stdio.h>

int main() {
    int n, digit;
    int max = 0, min = 9;

    printf("Enter a number: ");
    scanf("%d", &n);

    while (n > 0) {
        digit = n % 10;

        if (digit > max)
            max = digit;

        if (digit < min)
            min = digit;

        n = n / 10;
    }

    printf("Maximum digit = %d\n", max);
    printf("Minimum digit = %d\n", min);

    return 0;
}




#include <stdio.h>

// int main() {
//       int n,rem,arm=0;
//       printf("enter a number");
//       scanf("%d",&n);
//       while(n>0)
//       {
//           rem=n/10;
//           arm=arm+(rem*rem*rem);
//           n=n/10;
 
//       }
//       if(n=arm){
//       printf("it is a armstrong number");}
//       else
//       { printf("it is not a armstrong number");}
//     return 0;
// }




#include<stdio.h>
// int main()
// { int n,digit=0,remainder,count=0;
// printf("enter a number");
// scanf("%d",&n);
//  while(n>0)
//  { remainder=n%10;
//  digit+=remainder;
//  count++;
 
//  n=n/10;
//  } printf("the count is:%d",count);}
#include <stdio.h>

int main() {
    int n, i, j;
    scanf("%d", &n);

    for (i = 0; i < n; i++) {
        for (j = 0; j < n; j++) {

            if (i == j || i + j == n - 1 || i == n / 2 || j == n / 2)
                printf("* ");
            else
                printf("  ");
        }
        printf("\n");
    }

    return 0;
}

     array concept

#include <stdio.h>

int main() {
 
            int i,a[5],sum=0;
            printf("enter the 5 number");
            for(i=0;i<5;i++)
            { scanf("%d",&a[i]);
            sum+=a[i];}
            printf("%d",sum);
 
 

    return 0;
}
 




 #include<stdio.h>
// int main()
// {
//     int i,n;
//     scanf("%d",&n);
//     int a[n];
//     for(i=0;i<n;i++)
//     {
//         scanf("%d",&a[i]);
 
//     }
//     for(i=n-1;i>=0;i--)
//     {
//         printf("%d",a[i]);
//     }
// }


#include <stdio.h>
 

// int main() {
 
//       int i,n;
//       printf("enter the number");
//       scanf("%d",&n);
//       int a[n];
 
//         for(i=0;i<=n;i++)
//         { scanf("%d",&a[i]);
//         }
//         for(i=0;i<n;i++)
//         { printf("%d",a[i]);
//         }

//     return 0;
// }
