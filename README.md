public class NumberEvaluation {

    public static void main(String[] args) {
        System.out.print("Enter an integer: ");

        Scanner scan = new Scanner(System.in);

        int number = scan.nextInt();
        
        if (number > 0) {

            System.out.print(number + " is Positive");
        } else if (number < 0) {

            System.out.print(number + " is Negative");
        } else {
            System.out.print(number + " is Zero");
        }

        if (number % 2 == 0) {
            System.out.print(" and Even");
        } else {
            System.out.print(" and Odd");
        }
    }
}
