# ShubhamPreWorkAssignmentSolution
# CheckPalindromeNumber



package com.company;
import java.util.Scanner;
Public Class Main{
 public static void main(String[] args) {
        int sum, n, c=0, rem=0;
  Scanner sc = new Scanner(System.in);
        System.out.print("Please enter the number");
        n = sc.nextInt();
        sum = n;
   while(n>0);
        {
         rem= n%10;
            sum= (sum*10) + rem;
            n= n/10;
        }
        if(c==sum)
        {
            System.out.println("Its a Palindrome Number");
        }
        else
                {
            System.out.println("Its not a Palindrome number");
        }
    }


# Check Prime Number 

package com.company;
import java.util.Scanner;
 public class Main {
         public static void main(String[] args) {
             Scanner sc = new Scanner(System.in);
             System.out.println("Please enter the number");
             int n = sc.nextInt();
             int x = 0;
             for (int i = 2; i <= n-1; i++) {
                 if (n % i == 0) {
                     x = x + 1;
                 }
             }

             if (x == 0)
             {
                 System.out.println(n + " is a prime number");
             }
             else
             {
                 System.out.println(n + " is not a prime number");
             }
         }
     }
     

# Decreasing Star Pattern based on user input

pacakage com.company
 import java.util.Scanner;
 public class Main{
     public static void main(String[] args) {

         Scanner sc = new Scanner(System.in);
         System.out.println("Please enter the number of stars");
         int n = sc.nextInt();

         for(int i=1; i<=n; i++ )
         {
             for(int j=i; j<=n; j++)
             {
                 System.out.print("* ");
             }
             System.out.println();
         }

     }
 }
