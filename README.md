# Arrays-matrix-and-
Add two matrices

package matrixadditionexcercise;


public class MatrixAdditionExcercise {

    
    public static void main(String[] args) {
        
        // creating two matrices
        int a[][]={{1,3,4},{2,4,3},{3,4,5}};
        int b[][]={{1,3,4},{2,4,3},{1,2,4}};
        
        //creating another matrix to store the sum of 2 matrices
        int c[][]=new int[3][3]; //3rows 3 columns
        //adding addition of 2 matrices
        for (int i=0;i<3;i++){
            for (int j=0;j<3;j++){
                c[i][j]=a[i][j]+b[i][j];
                
                System.out.println(c[i][j]+"");
            }
            System.out.println();  //new line
        }
    }
    
}
