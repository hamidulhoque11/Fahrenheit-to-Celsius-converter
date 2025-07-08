# Fahrenheit-to-Celsius-converter

import java.util.Scanner;
class Main {
   public static void main (String [] args){
    Scanner sc= new Scanner(System.in);
    
    System.out.print("Enter the Fahrenheit:");
    double fahrenheit=sc.nextDouble();
    
    double celsius=0.55 * fahrenheit-32;
    System.out.println("Celsius is="+celsius);
    
      
    }
}
