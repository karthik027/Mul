# Mul
import java.util.*;
import java.io.*;
public class Mul
{
  public static void main(String args[])
  {
    int z=1;
    Scanner sc=new Scanner(System.in);
    int a=sc.nextInt();
    int mul=a;
    String b=String.valueOf(a);
    int l=b.length();
    char[] c=b.toCharArray();
    for(int i=0;i<l;i++)
    {
      int k=c[i]-48;
      //System.out.println(k);
      z=z*k;
    }
    mul=mul*z;
    System.out.println(mul);
  }
}
