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
