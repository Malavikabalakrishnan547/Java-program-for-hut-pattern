// Java-program-for-hut-pattern
public class pattern {

    public static void main(String args[]) {
        int a, b, c, d;
        for (a = 1; a <= 9; a++) {
            for (b = 9; b >= a; b--) {
                System.out.print(" ");
            }
            for (b = 1; b <= a; b++) {
                System.out.print("* ");
            }
            System.out.println();
        }

        //stem
        for (a = 1; a <= 8; a++) {
            System.out.print(" ");

            for (b = 0; b > 0; b--) {
                System.out.print(" ");
            }
            for (c = 2; c > 0; c--) {
                System.out.print("|\t\t");
            }
            System.out.println();
        }

        //base
        for (a = 1; a <= 3; a++) {

            for (b = 1; b <= 18; b++) {
                System.out.print("-");
            }
            System.out.print("\n");

            //stem2
        }
        for (a = 1; a <= 8; a++) {
            System.out.print(" ");

            for (b = 0; b > 0; b--) {
                System.out.print(" ");
            }
            for (c = 2; c > 0; c--) {
                System.out.print("|\t\t");
            }
            System.out.println();
        }

        //base
        for (a = 1; a <= 3; a++) {

            for (b = 1; b <= 18; b++) {
                System.out.print("-");
            }
            System.out.print("\n");

        }
    }
}
