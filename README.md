# xxxanonymousxxx
import java.util.Scanner;

public class calculator2
    {
        public static void main(String args[])
        {
            int ans,a,b,c;
            System.out.println("enter one integers");
            Scanner input = new Scanner(System.in);
            a = input.nextInt();
            System.out.println("enter one integers");
            
            b = input.nextInt();
            System.out.println(" If you want to add(1),subtract(2),multiply(3),divide and know the remainder(4),,divide and know the quotient(5)");
            
            c = input.nextInt();
            switch(c)
            {
            case 1:
            System.out.println(ans=a+b);
            break;
            case 2:
             System.out.println(ans=a-b);
             break;
             case 3:
             System.out.println(ans=a*b);
             break;
             case 4:
             System.out.println(ans=a/b);
             break;
             default:
              System.out.println("we are improving");
            }
        }
    } 
