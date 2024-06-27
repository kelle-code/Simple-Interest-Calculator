
### README for Simple Interest Calculator

```markdown
# Simple Interest Calculator

This is a simple interest calculator program implemented in Java. It calculates the simple interest based on the principal amount, rate of interest, and time period.

## How to Use

1. The program will prompt you to enter the principal amount.
2. Enter the principal amount and press Enter.
3. The program will prompt you to enter the rate of interest.
4. Enter the rate of interest and press Enter.
5. The program will prompt you to enter the time period in years.
6. Enter the time period in years and press Enter.
7. The program will display the calculated simple interest.

## Code Example

```java
import java.util.Scanner;

public class SimpleInterestCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.println("Enter the principal amount: ");
        double principal = scanner.nextDouble();
        
        System.out.println("Enter the rate of interest: ");
        double rate = scanner.nextDouble();
        
        System.out.println("Enter the time in years: ");
        int time = scanner.nextInt();
        
        double simpleInterest = (principal * rate * time) / 100;
        
        System.out.println("The simple interest is: " + simpleInterest);
        scanner.close();
    }
}
