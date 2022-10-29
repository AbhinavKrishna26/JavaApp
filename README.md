# JavaApp
This is a basic Java Text Editor application. Most suitable for beginners and learners.
# Making a Java App
lol
 AbhinavKrishna26-Dev

Its this time of the year again! Hacktoberfest 2022!
hello

Making a Java app cannot be easier than this. Try it out. Contribute here this hacktoberfest 2020.

hello
Making a Java cannot be easier than this. Try it out. Contribute here this hacktoberfest 2020.
This project features a basic java text editor.

See you Soon!
Hacktoberfest 2021
Its this time of the year again!
Hacktoberfest 2022!
 master
 AbhinavKrishna26-Dev
 hello 2k22
 
contact

hello Hacktober


hello
hello

// contact me 8002463989
 master

rishav4101-patch-4
``` 
import java.util.Scanner;  
public class ATMExample  
{  
    public static void main(String args[] )  
    {  
        int balance = 100000, withdraw, deposit;  
        Scanner sc = new Scanner(System.in);  
          
        while(true)  
        {  
            System.out.println("Automated Teller Machine");  
            System.out.println("Choose 1 for Withdraw");  
            System.out.println("Choose 2 for Deposit");  
            System.out.println("Choose 3 for Check Balance");  
            System.out.println("Choose 4 for EXIT");  
            System.out.print("Choose the operation you want to perform:");  
               
            int choice = sc.nextInt();  
            switch(choice)  
            {  
                case 1:  
        System.out.print("Enter money to be withdrawn:");  
  
        withdraw = sc.nextInt();  
                       
        if(balance >= withdraw)  
        {  
            balance = balance - withdraw;  
            System.out.println("Please collect your money");  
        }  
        else  
        {   
            System.out.println("Insufficient Balance");  
        }  
        System.out.println("");  
        break;  
   
                case 2:  
                      
        System.out.print("Enter money to be deposited:");   
        deposit = sc.nextInt();  
                      
        balance = balance + deposit;  
        System.out.println("Your Money has been successfully depsited");  
        System.out.println("");  
        break;  
   
 
        System.out.println("Balance : "+balance);  
        System.out.println("");  
        break;  
   
 
        System.exit(0);  
            }  
        }  
    }  
}  
```
#### In Java, we can create an ATM program for representing ATM transection. In the ATM program, the user has to select an option from the options displayed on the screen. The options are related to withdraw the money, deposit the money, check the balance, and exit.

#### To withdraw the money, we simply get the withdrawal amount from the user and remove that amount from the total balance and print the successful message. To deposit the money, we simply get the deposit amount from the user, add it to the total balance and print the successful message.

## Java Swing Library

Java Swing tutorial is a part of Java Foundation Classes (JFC) that is used to create window-based applications. It is built on the top of AWT (Abstract Windowing Toolkit) API and entirely written in java.

The javax.swing package provides classes for java swing API such as JButton, JTextField, JTextArea, JRadioButton, JCheckbox, JMenu, JColorChooser etc.
