public class Main {
    public static void main(String[] args) {
        double taxRate = 0.05;
        double item = 0.00;
        double total;
        double tax;
        System.out.printf("Enter the price of item $");
        Scanner input = new Scanner(System.in);
        item = input.nextDouble();
        tax = item * taxRate;
        total = tax + item;
        System.out.printf("The tax is $" + tax);
        System.out.printf("The total price is $" + total);
    }
}
