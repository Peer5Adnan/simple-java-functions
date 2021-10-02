# simple-java-functions
import java.util.Scanner;
 class two {
     int num1;
     int num2;

     void result() {
         int i=0;
         while (num2 > num1) {
         i++;
             System.out.print("  " + i);
             if (i == 20)break;
         }
     }
     void change(int one, int two) {
         num1 = one;
         num2 = two;
     }
 }
class One
{
    public static void main(String args[])
    {
        Scanner a=new Scanner(System.in);
        System.out.println("enter two numbers");
        int b,c;
        b=a.nextInt();
        c=a.nextInt();
        two obj=new two();
        obj.change(b,c);
        obj.result();
    }
}
