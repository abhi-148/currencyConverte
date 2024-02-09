import java.util.Scanner;

 class CurrencyConverter {
    public static void main(String[] args) {
        // Hardcoded exchange rate (for demonstration purposes)
        double usdToInr = 73.55; // 1 USD = 73.55 INR (as of the last update)

        Scanner scanner = new Scanner(System.in);

        // Get input from user
        System.out.print("Enter amount in USD: ");
        double amountUSD = scanner.nextDouble();

        // Convert to INR
        double amountINR = amountUSD * usdToInr;

        // Display result
        System.out.println("Amount in INR: " + amountINR);

        scanner.close();
    }
}
