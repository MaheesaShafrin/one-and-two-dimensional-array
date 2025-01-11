# one-and-two-dimensional-array
public class ArrayExamples {
    public static void main (String [] args) {
        // Single-dimensional array
        Int [] singleArray = {1, 2, 3, 4, 5};
        System.out.println("Single-dimensional array:");
        for (int i = 0; i < singleArray.length; i++) {
            System.out.print(singleArray[i] + " ");
        }
        System.out.println();
        // Two-dimensional array
        int[][] twoDimensionalArray = {
            {1, 2, 3},
            {4, 5, 6},
            {7, 8, 9}
        };
        System.out.println("\nTwo-dimensional array:");
        for (int i = 0; i < twoDimensionalArray.length; i++) {
            for (int j = 0; j < twoDimensionalArray[i].length; j++) {
                System.out.print(twoDimensionalArray[i][j] + " ");
            }
            System.out.println();
        }
        Output:
Single-dimensional array:
1 2 3 4 5


Two-dimensional array:
1 2 3
4 5 6
7 8 9


[Program finished]
