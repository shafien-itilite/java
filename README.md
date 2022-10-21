class FibonacciExample1{  
public static void main(String args[])  
{    
 int n1=0,n2=1,n3,i,count=10;    
 System.out.print(n1+" "+n2);//printing 0 and 1    
    
 for(i=2;i<count;++i)//loop starts from 2 because 0 and 1 are already printed    
 {    
  n3=n1+n2;    
  System.out.print(" "+n3);    
  n1=n2;    
  n2=n3;    
 }    
  
}}  
// ASCII value

public class PrintAsciiValueExample1   
{  
public static void main(String[] args)   
{  
// character whose ASCII value to be found  
char ch1 = 'a';  
char ch2 = 'b';  
// variable that stores the integer value of the character  
int asciivalue1 = ch1;  
int asciivalue2 = ch2;  
System.out.println("The ASCII value of " + ch1 + " is: " + asciivalue1);  
System.out.println("The ASCII value of " + ch2 + " is: " + asciivalue2);  
}  
}  