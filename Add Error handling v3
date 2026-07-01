import java.util.Scanner;

public class Calculator {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        double num1, num2, result;
        int choice;

        System.out.println("--- Erum Smart Calculator v3 ---");

        System.out.print("Enter first number: ");
        num1 = sc.nextDouble();

        System.out.print("Enter second number: ");
        num2 = sc.nextDouble();

        System.out.println("\nWhat to do?");
        System.out.println("1. Add +");
        System.out.println("2. Subtract -");
        System.out.println("3. Multiply *");
        System.out.println("4. Divide /");
        System.out.print("Enter choice 1,2,3,4: ");
        choice = sc.nextInt();
        switch (choice) {
            case 1:
                result = num1 + num2;
                System.out.println("\nResult: " + result);
                break;
            
            case 2:
                result = num1 - num2;
                System.out.println("\nResult: " + result);
                break;

            case 3:
                result = num1 * num2;
                System.out.println("\nResult: " + result);
                break;

            case 4:
              
                if (num2 == 0) { 
                    System.out.println("\nError: Cannot divide by zero!"); 
                } else { 
                    result = num1 / num2;
                    System.out.println("\nResult: " + result);
                }
                break;
            
            default:
                System.out.println("\nError: Invalid Choice! Enter 1 to 4.");
        }
        
        sc.close();
    }
}
