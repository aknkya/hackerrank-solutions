# hackerrank-solutions
import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {

    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int[] dizi=new int[n];
        for(int i=0;i<n;i++){
            dizi[i]=sc.nextInt();
            //System.out.println(dizi[i]);
        }
     
      int count=0;
     for(int z=0;z<n;z++){
         for(int t=z;t<n;t++){
         int x=z+t;
             if(x>n) {
            x=n; 
         }
             int[] ints1 = Arrays.copyOfRange(dizi, z, t+1);
             int toplam=0;
             for(int c=0;c<ints1.length;c++) {
                 
                 toplam=toplam+ints1[c];
                                                                
             }
             
             if(toplam<0) {
                 count=count+1;                    
                 
             }
             
            /* System.out.print(Arrays.toString(ints1));
                System.out.println("toplam="+toplam);
                System.out.println("count="+count);*/
      
             }}
            System.out.println(count);
     

    }
}

