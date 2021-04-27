# task_2.3


public class Main {

    public static void main(String[] args) {

        int line [][] = new int [10][];

        for (int i = 0; i < 10; i++) {
            line [i] = new int [i+1];
            for (int j = 0; j < i+1; j++) {
                line [i] [j] = 8;
            }
        }

        for (int i = 0; i < 10; i++) {
            for (int j = 0; j < i+1; j++) {
                System.out.print (line [i][j]);
            }
            System.out.println("");
        }
    }
}
