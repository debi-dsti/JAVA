# JAVA
good programming langue of all time, happy learning.



first progect in java.

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package firstproject;
import java.util.Scanner;

import javax.swing.JOptionPane;

public class firstproject
{

    public static void main(String[] args) 
    {
        int num1;
        int num2;
        String operation;


        Scanner input = new Scanner(System.in);

        System.out.println("first number");
        num1 = input.nextInt();

        System.out.println("second number");
        num2 = input.nextInt();
      Scanner op = new Scanner(System.in);

        System.out.println("Please enter operation");
        operation = op.next();

        if (operation == "+");
        {
            System.out.println("your answer is" + (num1 + num2));
        }
        if  (operation == "-");
        {
            System.out.println("your answer is" + (num1 - num2));
        }

        if (operation == "/");
        {
            System.out.println("your answer is" + (num1 / num2));
        }
        if (operation == "*")
        {
            System.out.println("your answer is" + (num1 * num2));
        }


    }
}
