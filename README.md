# TRANSPOSE-OF-A-MATRIX
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        int c=0;
        Scanner sc= new Scanner(System.in);
          System.out.println("Enter array length: ");
        int n=sc.nextInt();// Array length
         int [][]a=new int[n][n];
          System.out.println("Enter array elements: ");
        for(int i=0;i<n;i++){
            for(int j=0;j<n;j++){
            int k=sc.nextInt();
            a[i][j]=k;
            }
        }
         System.out.println("Normal matrix: ");
        for (int i=0;i<n;i++){
            for(int j=0;j<n;j++){
             System.out.print(a[i][j]+" ");
            }
            System.out.println();
        }
         System.out.println("Transpose matrix: ");
        for (int i=0;i<n;i++){
            for(int j=0;j<n;j++){
             System.out.print(a[j][i]+" ");
            }
            System.out.println();
        }
    }
}
