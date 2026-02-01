# input2Darrays
input2Darrays
import java.util.*;
public class input2Darrays {
    public static void main(String[] args) {
        int matrix[][] = new int[3][3];
        int n = matrix.length; int m = matrix[0].length;
        Scanner sc = new Scanner(System.in);
        for(int i = 0; i < n; i++){
            for(int j = 0; j < m; j++){
                matrix[i][j] = sc.nextInt();
            }
        }
        for(int i = 0; i < n; i++){
            for(int j = 0; j < m; j++){
                System.out.print(matrix[i][j] + " ");
            }
            System.out.println();
        }
    }
    
}
Enter the elements of the matrix
/*1 2 3 4 5 6 7 8 9
1 2 3 
4 5 6 
7 8 9 */
