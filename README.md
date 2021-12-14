# method-to-finrd-min-number
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

public class Main
{

   static int min(int n1,int n2,int n3)
    {
        int minNumber=n1;
        if (minNumber > n2)
            minNumber=n2;
        if (minNumber>n3)
            minNumber=n3;

            return minNumber;
    }
    public static void main (String args[])
    {
        Scanner k=new Scanner(System.in);
        int x,y,z;
        System.out.println("Enter #1 :");
        x=k.nextInt();
        System.out.println("Enter #2 :");
        y= k.nextInt();
        System.out.println("Enter #3 :");
        z=k.nextInt();
        System.out.println("min =" +min(x,y,z));
    }
}

 
