# Middle-word
it will give the middle word of string
import java.util.Scanner;

public class middleword {
    public middleword() {
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the String: ");
        String s = sc.nextLine();
        System.out.println(middle(s));
    }

    public static String middle(String s) {
        return s.length() % 2 == 0 ? s.substring(s.length() / 2, s.length() / 2 + 2) : s.substring(s.length() / 2 + 1);
    }
}
