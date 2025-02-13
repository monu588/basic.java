import java.util.Scanner;

public class aP3 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println(" number");
        int n = sc.nextByte();
        int a = 2, b = 3;
        for (int i = 2; i <= n; i++) {
            System.out.println(a);
            a += b;
        }
    }

