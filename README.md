# tamirinta9
package tamirinta;

public class tamirinta9 {

    public static void main(String[] args) {
        System.out.println("Programs can be easy or");
        System.out.println("difficult to read, depending");
        System.out.println("upon their format.");
        System.out.println();
        System.out.println("Everyone, including yourself,");
        System.out.println("will be happier if you choose");
        System.out.println("to format your programs.");
    }

}

class Messy {

    public static void main(String[] args) {
        message();
        System.out.println();
        message();
    }

    public static void message() {
        System.out.println("I really wish that");
        System.out.println("I had formatted my source");
        System.out.println("code correctly!");
    }
}

class ComputePay {

    public static void main(String[] args) {
        // Calculate my pay at work, based on how many hours I worked each day
        int totalHours = 4 + 5 + 8 + 4;
        double salary = 8.75;
        double pay = totalHours * salary;
        double taxRate = 0.20;
        double taxesOwed = pay * taxRate;

        System.out.println("My total hours worked:");
        System.out.println(totalHours);
        System.out.println("My hourly salary:");
        System.out.println("$" + salary);
        System.out.println("My total pay:");
        System.out.println(pay);
        System.out.println("My taxes owed:");
        System.out.println(taxesOwed);
    }
}

class Count2 {

    public static void main(String[] args) {
        for (int i = 1; i <= 4; i++) {
            System.out.println("2 times " + i + " = " + (2 * i));
        }
    }
}
