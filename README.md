# Simple-Interest-
import java.util.Scanner;
Public class SIMPLEINTEREST {

    Public static void main(String[]args){

        Scanner sc = new Scanner(System.in);
        System.out.print("Enter the principal amount:");
        double principal = sc.nextDouble();
        System.out.print("Enter the annual interest rate:");
        double rate = sc.nextDouble();
        System.out.print("Enter time in years:");
        double time = sc.nextDouble();
        double simpleinterest = (principal * rate * time)/100;
        System.out.println("Simple Interest : " + simpleinterest);
    }
}

OUTPUT:

Enter the principal amount:5000
Enter the annual interest rate:4.5
Enter time in years:5
Simple Interest : 1125.0
