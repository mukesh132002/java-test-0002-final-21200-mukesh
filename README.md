# java-test-0002-final-21200-mukesh
Final Project Assignment - This repository contains the complete final project code and documentation.
public class Main {
    public static void main(String[] args) {
        int n = 5;

        for (int i = 1; i <= n; i++) {

            // print spaces
            for (int j = 1; j <= (n - i); j++) {
                System.out.print("  ");
            }

            // increasing numbers
            for (int j = 1; j <= i; j++) {
                System.out.print(j + " ");
            }

            // decreasing numbers
            for (int j = i - 1; j >= 1; j--) {
                System.out.print(j + " ");
            }

            System.out.println();
        }
    }
}
