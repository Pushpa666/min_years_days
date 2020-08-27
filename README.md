# min_years_days

Java program by pushpa

1.import java.util.Scanner;

2.public class Exercise 4{

3.   Public static void main (string[]strings){

         double minutesInyear=60*24*365;
         
         Scanner input=new Scanner(System.in);
         
         System.out.print("Input the number of minutes:");
        
         double min=input.nextDouble();

         long years=(long) (min/minutesIn year);
         
         int days=(int) (min/60/24)%365;

         System.out.println((int)min+"minutes is approximately"+years+"years and"+days+"days");
         }
    }

