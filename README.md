# 10.FACTORIAL-OF-A-NUMBER-USING-LOOP

package factorialnumusingloop;
import java.util.Scanner;
public class Factorialnumusingloop {
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter a num:");
        int num=sc.nextInt();
        int factorial=1;
        for(int i=1;i<=num;i++){
            factorial *= i;
        }
        System.out.println("Factorial of" + num + "is"+factorial);
    }
    
}


O/P

run:
Enter a num:
5
Factorial of5is120
BUILD SUCCESSFUL (total time: 12 seconds)

