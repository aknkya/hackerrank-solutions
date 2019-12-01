# hackerrank-solutions
import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {
    
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        double payment = scanner.nextDouble();
        scanner.close();
        Locale en = new Locale("en", "US");      
        Locale ind = new Locale("en", "IN");  
        Locale chn = new Locale("en", "US");  
        Locale fr = new Locale("en", "US");  
       NumberFormat currencyend = NumberFormat.getCurrencyInstance(Locale.US);
       NumberFormat currencyind = NumberFormat.getCurrencyInstance(ind);
       NumberFormat currencychn = NumberFormat.getCurrencyInstance(Locale.CHINA);
       NumberFormat currencyfr = NumberFormat.getCurrencyInstance(Locale.FRANCE);

       System.out.println("US: "+currencyend.format(payment));
       System.out.println("India: " +currencyind.format(payment));
       System.out.println("China: " +currencychn.format(payment));
       System.out.println("France: " +currencyfr.format(payment));
        
       /* System.out.println("US: " + us);
        System.out.println("India: " + india);
        System.out.println("China: " + china);
        System.out.println("France: " + france);*/
    }
}

