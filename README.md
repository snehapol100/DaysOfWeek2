import java.util.*;
import java.lang.*;
public class Even_Or_Odd
{
     public static void main(String [] args)
     {
        int P=0;
        System.out.print("\n Enter a number:");
        Scanner Sc=new Scanner(System.in);

        P=Sc.nextInt();

        if(P%2==0)
        {
            System.out.print("\n Number is Even");
        }
        else
        {
            System.out.print("\n Number is Odd");
        }
     }
}
