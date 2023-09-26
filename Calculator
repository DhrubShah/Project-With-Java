# Project-With-Java
Programming to make Calculator


        import java.util.Scanner;
        public class Calculator {
        public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        
        System.out.println("Welcome to the Calculator!");
        System.out.print("Enter the first number: ");
        double num1 = input.nextDouble();
        
        System.out.print("Enter the operator (+, -, *, /): ");
        char operator = input.next().charAt(0);
        
        System.out.print("Enter the second number: ");
        double num2 = input.nextDouble();
        
        double result;
        
        switch(operator) {
            case '+':
                result = num1 + num2;
                break;
            case '-':
                result = num1 - num2;
                break;
            case '*':
                result = num1 * num2;
                break;
            case '/':
                if (num2 != 0) {
                    result = num1 / num2;
                } else {
                    System.out.println("Error: Division by zero");
                    return;
                }
                break;
            default:
                System.out.println("Invalid operator");
                return;
        }
        
        System.out.println("Result: " + result);
        
        input.close();
    }
    }
