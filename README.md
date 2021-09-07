import java.util.Scanner;
public class JavaExample{
     
    public static void main(String[]args)
     { 
       int number1=10,number2=20,number3=30;
        
       if(number1>=number2&&number1>=number3)
         System.out.println(number1+"is the largest Number");
      
       else if (number2>=number1 && number2>=number3)
         System.out.println(number2+"is the largest Number");
    
       else
         System.out.println(number3+"is the largest Number");
     }
    }
